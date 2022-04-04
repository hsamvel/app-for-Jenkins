pipeline {
  agent any
  stages {
    stage('') {
      steps {
        catchError(buildResult: 'Failure', message: 'Something', stageResult: 'Failure', catchInterruptions: true) {
          sh '''sleep 20
'''
        }

      }
    }

  }
}