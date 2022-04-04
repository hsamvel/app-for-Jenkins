pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        catchError(buildResult: 'Failure', message: 'Error occured')
      }
    }

  }
}