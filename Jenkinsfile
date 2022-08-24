pipeline{
  agent any

  stages{
    stage("build maven"){
      steps{
        sh 'mvn clean install'
      }
    }

    stage("build docker image"){
      steps {
        sh 'docker build -t devops/kube-java .'
      }
    }
  }
}
