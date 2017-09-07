pipeline {
  agent {
    docker {
      image 'nginx:alpine'
    }
    
  }
  stages {
    stage('init') {
      steps {
        sh 'docker run --name doe-www -p 81:80 -v /vagrant/www/:/usr/share/nginx/html'
      }
    }
  }
}