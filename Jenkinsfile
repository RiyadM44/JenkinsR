pipeline {
    agent any

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                sh 'sudo docker run -d -p 80:80 --name hasaki nginx'
            }
        }
    }
}
