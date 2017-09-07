pipeline {
  agent {
    docker {
      image 'nginx:alpine'
    }
    
  }
  stages {
    stage('init') {
      steps {
        sh 'which docker'
      }
    }
  }
}