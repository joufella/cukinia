pipeline {
    agent { label "ryzen" }

    environment {
        CI = 'true'
    }

    stages {
        stage('Build') {
            steps {
                sh 'echo Starting build'
                sh 'ls -la'
            }
        }

        stage('Test') {
            steps {
                sh 'echo Starting test'
            }
        }
    }
}
