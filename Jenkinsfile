pipeline {

    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Code downloaded from GitHub'
            }
        }

        stage('Docker Build') {
            steps {
                sh 'docker build -t cnas-test:v1 .'
            }
        }

    }
}
