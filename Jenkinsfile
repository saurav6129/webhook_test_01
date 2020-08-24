pipeline {
    agent none
    stages {
        stage('Python build') {
			agent {
				docker {
					image 'python:2-alpine'
				}
			}
			
			
			steps {
				sh 'python --version' 
				echo 'testing python version as well as webhook .'
				echo'let us see'
				echo 'changed few things'
			
			}
		}
	}
}