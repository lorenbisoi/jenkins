pipeline {
	agent any

	stages {
	    stage('Checkout') {
	        steps {
				checkout scm			        }
		    }
		stage('Build') {
	        steps {
				sh '/home/loren/.jenkins/workspace/mvn install'
	        }
		}
		stage('Deployment') {
			steps {
				sh 'echo deployment is succussful!'
			}
		}

	}
}
