//#DECLERATIVE

pipeline{
	agent any
	stages{
		stage("Build"){
			steps{
				echo "Build"
			}
		}

		stage("QA"){
			steps{
				echo "QA"
			}
		}

		stage("Integration"){
			steps{
				echo "Integration"
			}
		}
	}

	post {
		always {
				echo "I run always"
		}
		success {
				echo "I run successfully"
		}
		failure {
				echo "I have failed"
		}
	}
}

/*node{
	echo "Build"
	echo "QA"
	echo "Integration Test"
}

node {
	stage('Build') {
		echo "Build"
	}
	stage('Test') {
		echo "Test"
	}
	stage('QA- Integration') {
		echo "Integration"
	}
}*/
