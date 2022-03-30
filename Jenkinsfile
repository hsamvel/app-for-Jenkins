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
        writeFile(file: 'from_build', text: 'Existence of this file speaks about succesfull build', encoding: 'utf-8')
        sh 'cat from_build'
      }
    }

  }
  environment {
    MESSAGE = 'Hello world!'
    CURRENT_USER = 'Sam'
  }
}