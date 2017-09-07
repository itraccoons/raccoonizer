pipeline {
  agent {
    docker {
      image 'bash:alpine'
    }
    
  }
  stages {
    stage('init') {
      steps {
        echo 'Init'
      }
    }
    stage('Run') {
      steps {
        sh 'docker -v'
      }
    }
  }
}