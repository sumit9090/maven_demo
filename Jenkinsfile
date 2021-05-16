node{
stage('SCM Checkout')
{
git'https://github.com/sumit9090/maven_demo'
}

stage('Compile-Package')
{
  def mvnHome=tool name: 'Default', type: 'maven'
  sh "${mvnHome/bin/mvn package}"
}
}
