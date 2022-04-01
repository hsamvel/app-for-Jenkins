pipeline {
  agent any
  stages {
    stage('Error Handling') {
      steps {
        warnError(message: 'Error occured') {
          sh '''sleep 10
'''
        }

      }
    }

  }
  environment {
    MESSAGE = 'Hello world!'
    CURRENT_USER = 'Sam'
  }
}