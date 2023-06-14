pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        script {
          withDockerRegistry(credentialsId: 'dockerhub_creds') {
            sh 'docker build -t bjgomes/jenkins-pipeline .'
            sh 'docker push bjgomes/jenkins-pipeline'
          }
        }
      }
    }
  }
}



