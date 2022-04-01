pipeline {
  agent any
  stages {
    stage('Error Handling') {
      steps {
        echo '${MESSAGE}'
        error 'Error occures'
      }
    }

  }
  environment {
    MESSAGE = 'Hello world!'
    CURRENT_USER = 'Sam'
  }
}