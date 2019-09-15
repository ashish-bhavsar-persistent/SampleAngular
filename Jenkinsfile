pipeline {
agent any

	stages {
		stage('Build') {
			steps {
				nodejs(nodeJSInstallationName: 'Node 12.x') {
					sh 'npm config ls'
				}
			}
		}
	}
}