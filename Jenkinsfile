pipeline {
  agent {
    docker {
      image 'node:latest'
    }
    
  }
  stages {
    stage('init') {
      steps {
        sh 'npm install grunt-cli'
      }
    }
  }
}