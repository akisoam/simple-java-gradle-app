pipeline {
    agent {
		docker {
			image 'gradle:alpine'
	
		}
	}
    
    stages {
        stage('Build') {
            steps {
				sh 'gradle clean build'
            }
		}
		
	}
}
