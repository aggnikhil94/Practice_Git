pipeline {
    agent any

    stages {
        stage('Create build output') {
            steps {
                echo 'Building..'
                // Make the output directory.
                sh "mkdir -p output"
                // Write an useful file, which is needed to be archived.
                writeFile file: "output/usefulfile.txt", text: "This file is useful, need to archive it."
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
