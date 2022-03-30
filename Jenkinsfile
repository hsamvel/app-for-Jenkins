pipeline {
  agent {
    node {
      label 'Linux_Slave_1'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh '''echo "This is build stage"
echo "Start building...... "'''
        sh 'echo hello ${CURRENT_USER}'
        sh 'pwd'
      }
    }

  }
  environment {
    CURENT_DIR = 'Hello world!'
    CURRENT_USER = 'Sam'
  }
}