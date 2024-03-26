pipeline {
    agent any
    stages {
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                sh 'sudo docker-compose up -d'
            }
        }
    }
}
