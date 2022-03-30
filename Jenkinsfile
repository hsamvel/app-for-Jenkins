pipeline {
  agent {
    node{
    label 'Linux_Slave_1'
    }
  }
  environment {
  CURENT_DIR = 'Hello world!'
  }
  stages {
    stage('Build') {
      steps {
        sh '''echo "This is build stage"
echo "Start building...... "'''
        sh 'echo ${CURENT_DIR}'
        sh 'ifconfig eth0'
      }
    }

  }
}
