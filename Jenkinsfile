pipeline {
    agent any

    stages {
        stage('Create build output') {
            steps {
                echo 'Building..'
                dir('G:\\Nikhil') {
                  writeFile file:'dummy', text:''
                }
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
