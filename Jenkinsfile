node{
  stage('SCM Checkout'){
  git 'https://github.com/AjayKharde/GitTest.git'
  }
  stage('Java compile'){
  def javahome = tool name: 'MyJDK', type: 'jdk'
  sh "${javahome}\bin\javac *.java"
  }
}
