pipeline {
    agent any
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building Ammar'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing Ammar'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying Ammar'
            }
        }
    }
}
