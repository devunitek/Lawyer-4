pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Fatima-cloud-ops/lawyer-project-4.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Add build commands here if needed, e.g., npm install, composer install, etc.
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add test commands here if you have tests
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying project...'
                // Deployment steps go here later
            }
        }
    }
}
