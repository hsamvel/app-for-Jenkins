pipeline {
  agent any
  stages {
    stage('Error Handling') {
      steps {
        try {
          sh '''python.exe'''
        } catch (Exception e){
          sh "error found"
        }

      }
    }

  }
  environment {
    MESSAGE = 'Hello world!'
    CURRENT_USER = 'Sam'
  }
}
