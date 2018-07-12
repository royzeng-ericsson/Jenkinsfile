pipeline {
  agent {
    docker {
      image 'Alpine'
      args 'hostname -f'
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