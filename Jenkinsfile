pipeline{
  agent any

  stages{
    stage("build maven"){
      steps{
        sh 'mvn clean install'
      }
    }
  }
}
