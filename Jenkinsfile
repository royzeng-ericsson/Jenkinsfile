pipeline {
  agent {
    docker {
      args 'hostname -f'
      image 'alpine'
    }

  }
  stages {
    stage('Hostname') {
      steps {
        sh '''hostname
ip a'''
      }
    }
  }
}