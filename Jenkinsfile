pipeline {
	agent {
		docker {image 'httpd:latest'}
	}
		
	stages {
		stage('testing') {
			steps {
				sh '''
				apache2 -v
				'''
			}
		}
		

		}
}








