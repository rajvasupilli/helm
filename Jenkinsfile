pipeline {
    agent any

    stages {
        stage('Deploy') {
            steps {
                sh '''
                    helm install mynginx nginx
                '''
            }
        }
    }
}
