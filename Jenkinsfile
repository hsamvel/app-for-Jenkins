pipeline {
  agent any
  stages {
    stage('Error Handling') {
      steps {
        echo '${MESSAGE}'
        warnError(message: 'Error occures', catchInterruptions: true) {
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