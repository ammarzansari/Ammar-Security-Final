pipeline {
    agent any
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building your name'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing your name'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying your name'
            }
        }
    }
}
