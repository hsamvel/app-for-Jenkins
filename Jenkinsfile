pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                script{
                try {
                sh "python -version"
                }   catch (error){
                        echo 'error'
                 
                 }
                }
            }
        }
    }
}
