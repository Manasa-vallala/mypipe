pipeline {
	agent any
	stages {
	stage('Build') {
		steps {
		WithCredentials([UsernamePassword(CredentialID:'id1pat', UserVariable: 'GITHUB_CREDS_USR', PasswordVariable: 'GITHUB_CREDS_PSW')])
			{
				echo "my username : ${GITHUB_CREDS_USR}"
				echo "my password : ${GITHUB_CREDS_psw}"
			}
		}
	}
}
}

