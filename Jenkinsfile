pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url:'https://github.com/DhruvArora664/jenkins-project.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                bat 'echo Build completed successfully'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                bat 'echo Tests completed successfully'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                bat 'echo Deployment completed successfully'
            }
        }
    }
}
