pipeline {
    agent any
    tools {
        nodejs "NodeJS 18.8.0"
    }
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
