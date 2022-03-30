pipeline {
  agent any
  environment {
  CURENT_DIR = sh 'pwd'
  }
  stages {
    stage('Build') {
      steps {
        sh '''echo "This is build stage"
echo "Start building...... "'''
        sh 'echo ${CURENT_DIR}'
        sh 'ip addr'
      }
    }

  }
}
