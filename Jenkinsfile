pipeline {
  agent {
    docker {
      image 'docker:latest'
      args '-v /var/run/docker.sock:/var/run/docker.sock'
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
ls -la
docker -v'''
      }
    }
  }
}