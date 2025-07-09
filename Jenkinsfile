pipeline {
    agent any

    environment {
        // Global environment variables
        MY_NAME = 'Manasa'
        BUILD_TYPE = 'Release'
        PATH = "/usr/local/bin:$PATH" // override or extend existing
    }

    stages {
        stage('Print Info') {
            steps {
                echo "Hello, ${MY_NAME}"
                echo "Build type is ${BUILD_TYPE}"
                sh 'echo "Shell Path is $PATH"'
            }
        }
    }
}
