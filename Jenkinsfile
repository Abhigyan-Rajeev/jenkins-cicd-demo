pipeline {
    agent any

    triggers {
        pollSCM('H/2 * * * *')
    }

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out source code'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project'
                echo 'Build completed successfully'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests'
                echo 'All tests passed'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the project'
                echo 'Deployment completed successfully'
            }
        }
    }
}