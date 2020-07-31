pipeline {
    agent any

    stages {
        stage('Create build output') {
            steps {
                echo 'Building..'
                archiveArtifacts 'file7.js'
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
