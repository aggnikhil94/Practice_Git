pipeline {
    agent any

    stages {
        stage('Create build output') {
            steps {
                echo 'Building..'
                sh label: '', script: 'mkdir  G:\\Nikhil'
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
