pipeline {
	agent any

	stages {
	    stage('Checkout') {
	        steps {
				checkout scm			        }
		    }
		stage('Build') {
	        steps {
				sh '/home/loren/.jenkins/workspace/pipeline/mvn install'
	        }
		}
		stage('Deployment') {
			steps {
				sh 'echo deployment is succussful!'
			}
		}

	}
}
