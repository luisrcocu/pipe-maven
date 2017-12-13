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
				echo "PATH=${PATH}"
				echo "M2_HOME=${M2_HOME}"
				sh 'mvn clean install'
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
