pipeline {
    agent any
    stages {
        stage('Stage 1: Greeting') {
            steps {
                echo 'Hello from Jenkins Pipeline!'
            }
        }
        stage('Stage 2: Date and Time') {
            steps {
                sh 'date'
            }
        }
        stage('Stage 3: List Files') {
            steps {
                sh 'ls -la'
            }
        }
    }
}
