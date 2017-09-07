pipeline {
  agent {
    docker {
      image 'bash:latest'
    }
    
  }
  stages {
    stage('init') {
      steps {
        echo 'Init'
      }
    }
    stage('Checks') {
      steps {
        sh '''hostname
pwd
ls -la'''
      }
    }
  }
}