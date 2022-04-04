pipeline {
  agent any
  stages {
    stage('') {
      steps {
        catchError(buildResult: 'Failure', message: 'Something', stageResult: 'Failure', catchInterruptions: false) {
          sh '''sleep 20
'''
        }

      }
    }

  }
}
