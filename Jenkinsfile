pipeline {
agent any

	stages {
		stage('Build') {
			steps {
						nodejs(nodeJSInstallationName: 'Node 12.10.0') {
					sh 'npm config ls'
          sh 'npm test'
            }
			}
		}
	}
}
