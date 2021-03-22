pipeline {
    agent { label "ryzen" }

    environment {
        CI = 'true'
    }

    stages {
        stage('Build') {
            steps {
                sh 'echo Starting build v2'
                sh 'ls -la'
            }
        }

        stage('Test') {
            steps {
                sh 'echo Starting test'
                sh 'ls -la tests/'
            }
        }
    }
}
