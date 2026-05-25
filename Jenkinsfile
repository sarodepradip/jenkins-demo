pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Source code checked out'
            }
        }

        stage('Build') {
            steps {
                sh 'docker build -t pradipsarode/app:v1 .'
            }
        }
    }
}
