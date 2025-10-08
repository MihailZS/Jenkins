pipeline {
    agent any
    stages {
        stage('Stage 1: Greeting') {
            steps {
                echo 'Hello from Jenkins Pipeline!'
            }
        }
        stage('Stage 2: Current Date and Time') {
            steps {
                sh 'date'
            }
        }
        stage('Stage 3: List Files in Workspace') {
            steps {
                sh 'ls -la'
                sh 'cat test.txt'
            }
        }
        stage('Stage 4: Environment Variables') {
            steps {
                echo "Current Build Number: ${env.BUILD_NUMBER}"
                echo "Jenkins URL: ${env.JENKINS_URL}"
                echo "Workspace Path: ${env.WORKSPACE}"
            }
        }
    }
}
