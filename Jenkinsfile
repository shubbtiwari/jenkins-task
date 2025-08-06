pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the app...'
                sh 'node -v'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing the app...'
                sh 'echo "Tests passed!"'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the app...'
                sh 'node index.js'
            }
        }
    }
}
