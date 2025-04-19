pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Build the project
                sh 'mvn clean package'
            }
        }

        stage('Test') {
            steps {
                // Run your tests (if you have them)
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                // Deploy the application
                echo 'Deploying application...'
            }
        }
    }
}
