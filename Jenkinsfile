pipeline {
    agent any

    stages {
        stage('Create build output') {
            steps {
                echo 'Building..'
                mkdir G:\Nikhil
                writeFile file: 'groovy1.txt', text: 'Working with files the Groovy way is easy.'
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
