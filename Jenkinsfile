pipeline {
    agent any

    stages {
        stage('Create build output') {
            steps {
                echo 'Building..'
                   sh 'ls -l'
                    dir ('foo') {
                    writeFile file:'dummy', text:''
       }
       sh 'ls -l'
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
