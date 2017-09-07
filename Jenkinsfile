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
        ws(dir: '/vagrant/workdir')
      }
    }
    stage('Run') {
      steps {
        sh 'echo TEST'
      }
    }
  }
}