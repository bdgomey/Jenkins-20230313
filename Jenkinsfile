pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        sh 'docker build -t bjgomes/jenkins-pipeline .'
        sh 'docker push bjgomes/jenkins-pipeline'
      }
    }
  }
}
