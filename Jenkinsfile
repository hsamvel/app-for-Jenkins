pipeline {
  agent any
  stages {
    stage('Error Handling') {
      steps {
        warnError(message: 'Error occured') {
          sh '''python.exe

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