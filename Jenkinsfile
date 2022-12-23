pipeline {
    agent any
    
    triggers {
        cron('* * * * *')
    }
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
