pipeline {
    agent any

    stages {
        stage('Deploy') {
            steps {
                sh '''
                    helm upgrade --install mynginx nginx
                '''
            }
        }
    }
}
