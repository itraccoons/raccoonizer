pipeline {
  agent {
    docker {
      image 'nginx:alpine'
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
        sh 'whereis docker'
      }
    }
  }
}