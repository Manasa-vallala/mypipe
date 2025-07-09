pipeline {
    agent any

    environment {
        DEPLOY_ENV = 'staging'
        USER_NAME = 'manasa'
    }

    stages {
        stage ('Print Environment') {
            steps {
                sh 'echo "Deploying to ${env.DEPLOY_ENV} by ${env.USER_NAME}" '
            }
        }
    }
}
