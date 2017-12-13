pipeline {
	agent any
	tools {
		maven 'maven'
		jdk 'jdk1.8.0_151'
	}
	stages {
		stage('Build') {
			steps {
				echo 'Building...'
			}
		}
		stage('Test') {
			steps {
				echo 'Testing...'
			}
		}
		stage('Deploy') {
			steps {
				echo 'Deploying...'
			}
		}
	}
}
