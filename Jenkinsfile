pipeline {
  agent {
    docker {
      image 'golang:1.10.1-alpine'
    }
    
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Say Hello'
        sh 'go version'
      }
    }
  }
}