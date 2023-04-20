pipeline {
    agent any
    stages {
        stage('Init') {
            steps {
                echo 'Hi, this is init deveops project'
                echio 'We are starting the testing'
            }
        }
        stage('Build'){
            steps {
                echo 'Building Sample Maven Project'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying in staging area'
            }
        }
    }
}