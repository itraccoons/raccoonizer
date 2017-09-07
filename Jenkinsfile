pipeline {
  agent {
    docker {
      image 'nginx:alpine'
      args '-p 8111:80'
    }
    
  }
  stages {
    stage('init') {
      steps {
        echo 'init'
      }
    }
  }
}