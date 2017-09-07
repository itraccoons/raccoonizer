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
    stage('Check docker') {
      steps {
        sh '''hostname
pwd
ls -la
docker ps'''
      }
    }
    stage('Run container') {
      steps {
        sh '''docker rm doe-nginx
docker run --name doe-nginx -p 8111:80 -d nginx'''
      }
    }
  }
}