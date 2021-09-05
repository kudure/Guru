pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'python3.7 programm.py'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                echo 'Deploy done dummy text....'
            }
        }
    }
}
