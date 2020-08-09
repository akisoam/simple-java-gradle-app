pipeline {
	agent { label 'ubuntu' }   
    stages {
        stage('Build') {
            steps {
				sh 'gradle clean build'
            }
		}
		
	}
}
