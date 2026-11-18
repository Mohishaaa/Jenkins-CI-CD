pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'python3 -m py_compile app.py'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing the project...'
                sh 'python3 app.py'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment successful!'
            }
        }
    }
}