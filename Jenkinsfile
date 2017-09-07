pipeline {
  agent {
    docker {
      args '-p 8111:80'
      image 'nginx:alpine'
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