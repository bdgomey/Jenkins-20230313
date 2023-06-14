pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        echo 'Hello World'
        sh 'echo "Shell"'
      }
    }

    stage('docker_ps') {
      steps {
        sh 'docker ps'
      }
    }

  }
}