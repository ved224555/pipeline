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
				sh 'java -version'
			}
		}
		
		stage('deployment'){
			steps{
				echo 'deployed!!!'
			}
		}
	}
}
