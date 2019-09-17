pipeline {
agent any

	stages {
		stage('Build') {
			steps {
			    sh 'apt-get update'
          sh 'apt-get install nodejs'
          sh 'apt-get install npm'
					sh 'npm config ls'
          sh 'npm test'
				
			}
		}
	}
}
