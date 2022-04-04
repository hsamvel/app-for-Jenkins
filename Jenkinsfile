pipeline {
  agent any
  stages {
    stage('CatchingError') {
      steps {
        script{
          try {sh "python -version"
          }   catch (error){
            echo 'error'

          }
        }
      }
    }

  }
}
