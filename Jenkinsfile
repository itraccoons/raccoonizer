pipeline {
  agent none
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