pipeline {
    agent any

    stages {
        stage('Deploy') {
            steps {
                helm upgrade --install mynginx nginx
            }
        }
    }
}
