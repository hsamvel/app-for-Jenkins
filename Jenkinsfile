pipeline {
  agent any
  stages {
    stage('Error Handling') {
      steps {
        try {
          echo '${MESSAGE}'
          python.exe }
        catch (Exception err) {
          echo "there is an error"
        }
          
        }
    }

  }
  environment {
    MESSAGE = 'Hello world!'
    CURRENT_USER = 'Sam'
  }
}
