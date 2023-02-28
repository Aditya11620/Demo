pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello build'
            }
        }
         stage('Test') {
            steps {
                echo 'Hello test'
            }
        }
         stage('Deploy') {
            steps {
                echo 'Hello deploy'
            }
        }
    }
         post {
            always {
                emailext body :'new pipe from email',subject:'pipelineemail sended', to:'adityaraj.11620@gmail.com'
            }
        }
    }

