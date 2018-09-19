node{
stage('SCM Checkout'){
  
git 'https://github.com/krishna1292/30aug'
}
stage('Compile-Package'){
  def mvnHome = tool name: 'maven', type: 'maven'
  sh "${mvnHome}/bin/mvn package"
  
}
}   
