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
				bat '''javac "src/main.java"
					java "src/main.java"'''
			}
		}
	}
}
