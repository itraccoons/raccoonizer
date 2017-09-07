pipeline {
  agent {
    docker {
      image 'nginx:alpine'
    }
    
  }
  stages {
    stage('init') {
      steps {
        sh '''which docker
#docker run --name doe-www -p 81:80 -v /vagrant/www/:/usr/share/nginx/html:ro -d nginx:alpine'''
      }
    }
  }
}