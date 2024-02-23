pipeline {
    agent any
    tools{'nodejs'}

    stages {
        stage('Checkout') {
            steps {
                  https://github.com/janardhan0210/react1.git
            }
        }

        stage('Install Dependencies') {
            steps {
                // Install node dependencies
                sh 'npm install'
            }
        }

        stage('Build') {
            steps {
                // Build the React application
                sh 'npm run build'
            }
        }

        stage('Test') {
            steps {
                // Run tests (if applicable)
                // Replace this command with your testing command
                sh 'npm test'
            }
        }
    }

}
