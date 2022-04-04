pipeline {
  agent any
  stages {
    stage('CatchingError') {
      steps {
        sh '''python
'''
        catchError(buildResult: 'Failure', message: 'Something went wrong')
      }
    }

  }
}