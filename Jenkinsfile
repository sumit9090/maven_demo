node{
stage('SCM-Checkout)
      {
        git 'https://github.com/sumit9090/maven_demo.git'
      }

stage('Compile-Package')
{
  def mvnHome=tool name: tool name: 'Default', type: 'maven'
  echo "${mvnHome/bin/mvn package}"
}
}
