pipeline {
	agent any
    stages {
        stage('Build') {
            steps {
				sh 'gradle clean assembleRelease'
            }
		}
		
	}
}
