pipeline {
    agent any

    environment {
        DEPLOY_ENV = 'staging'
        USER_NAME = 'manasa'
    }

    stages {
        stage ('print Env') {
            steps {
                sh 'echo "Deploying to $DEPLOY_ENV by $USER_NAME" '
            }
        }
    }
}
