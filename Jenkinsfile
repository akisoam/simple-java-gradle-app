pipeline {
	agent {slave}    
    stages {
        stage('Build') {
            steps {
				sh 'gradle clean build'
            }
		}
		
	}
}
