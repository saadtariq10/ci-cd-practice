pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/saadtariq10/ci-cd-practice.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the application...'
                // Add your build commands here (e.g., mvn clean install, npm install)
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add test execution commands here (e.g., pytest, jest, JUnit)
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Add deployment steps (e.g., Docker, Kubernetes, SCP, AWS)
            }
        }
    }
}
