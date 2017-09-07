pipeline {
  agent {
    docker {
      image 'nginx:alpine'
      args '-p 8111:80 -v /vagrant/www:/usr/share/nginx/html'
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