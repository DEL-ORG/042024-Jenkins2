pipeline {
    agent any

    stages {
        stage('create a dir') {
            steps {
              sh '''
                mkdir jm
                rm -rf jm
                '''  
            }
        }
        stage('Create a file') {
            steps {

                sh '''
                touch text.txt
                rm -rf text.txt
                '''

            }
        }
        
    }
}
