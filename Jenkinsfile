pipeline {
	agent any
	stages {
	stage('Build') {
		steps {
		WithCredentials([UsernamePassword(Credential ID:'id1pat', User Variable: 'GITHUB_CREDS_USR', Password Variable: 'GITHUB_CREDS_PSW')])
			{
				echo "my username : ${GITHUB_CREDS_USR}"
				echo "my password : ${GITHUB_CREDS_psw}"
			}
		}
	}
}

