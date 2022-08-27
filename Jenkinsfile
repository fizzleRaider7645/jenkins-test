pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                npm ci
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
