pipeline {
  agent {
    docker {
      image 'node:latest'
    }
    
  }
  stages {
    stage('init') {
      steps {
        sh 'npm install mocha --save-dev'
      }
    }
    stage('test') {
      steps {
        sh './node_modules/mocha/bin/mocha test'
      }
    }
  }
}