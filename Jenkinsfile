pipeline {

    agent any

    stages {

        stage('Welcome') {
            steps {
                echo 'Welcome to Jenkins Pipeline'
            }
        }

        stage('Build') {
            steps {
                echo 'Build Started'
                echo 'Preparing Application'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Application'
                echo 'All Tests Passed'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Application Deployed Successfully'
            }
        }
    }
}
