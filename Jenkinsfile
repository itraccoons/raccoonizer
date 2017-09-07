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
    stage('Run') {
      steps {
        sh 'docker -v'
      }
    }
  }
}