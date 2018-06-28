pipeline {
  agent {
    docker {
      image 'node:alpine'
    }

  }
  stages {
    stage('') {
      steps {
        sh '''npm install
npm test'''
      }
    }
  }
}