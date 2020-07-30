pipeline {
    agent any

    stages {
        stage('Create build output') {
            steps {
                echo 'Building..'
    writeFile file: 'groovy1.txt', text: 'Working with files the Groovy way is easy.'
    sh 'ls -l groovy1.txt'
    sh 'cat groovy1.txt'
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
