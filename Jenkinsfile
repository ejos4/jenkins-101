pipeline {
	agent {
		node {
			label 'docker-agent-python'
		}
	}
	triggers {
		pollSCM '*/5 * * * *'
	}
	stages {
		stage('Build') {
			steps {
				echo "Building.."
				sh '''
				echo "doing build stuff.."
				'''
			}
		}
		stage('Test') {
			steps {
				echo "Testing.."
				sh '''
				echo "doing test stuff.."
				'''
			}
		}
		stage('Deliver....') {
			echo 'Deliver....'
			sh '''
			echo "doing delivery stuff"
			'''
		}		
	}
}
