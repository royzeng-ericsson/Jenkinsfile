pipeline {
  agent {
    node {
      label 'RSlave'
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