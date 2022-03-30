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
        sh 'pwd'
        sh 'ip addr'
      }
    }

  }
}
