pipeline {
    agent any

    stages {
        stage('Deploy') {
            steps {
                '''
                    helm install mynginx nginx
                '''
            }
        }
    }
}
