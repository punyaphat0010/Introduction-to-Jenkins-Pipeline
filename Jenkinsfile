pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                sh 'ls -l'   // List files in the workspace
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'ls -l'   // List files in the workspace
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                sh 'ls -l'   // List files in the workspace
            }
        }
    }
    post {
        success {
            echo 'Pipeline completed successfully 🎉'
        }
        failure {
            echo 'Pipeline failed ❌'
        }
    }
}