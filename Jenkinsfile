pipeline {
agent any

	stages {
		stage('Build') {
			steps {
			    
          sh 'sudo apt-get install nodejs'
          sh 'sudo apt-get install npm'
					sh 'npm config ls'
          sh 'npm test'
				
			}
		}
	}
}
