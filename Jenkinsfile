pipeline{
	agent any
	stages{
		stage('build'){
			steps{
				echo 'Building in process'			
			}
		}
		
		stage('testing'){
			steps{
				echo 'testing in process'			
			}
		}
		
		stage('deployment'){
			steps{
				sh 'javac main.java'
				sh 'java main'
			}
		}
	}
}
