pipeline {
    agent any
    stages {
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                sh 'docker-compose up -d'
            }
        }
    }
}
