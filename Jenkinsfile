//SCRIPTED
//DECLARATIVE
pipeline {
		agent any
		stages {
			stage('Build'){
				steps{
					echo "Build"
				}
			}
			stage('Test'){
				steps{
					echo "Test"
				}
			}
			stage('Integration Test'){
				steps{
					echo "Integration Test"
				}
			}
		} 
		
		post{
			always {
				echo 'I am Awesome'
			}
			success {
				echo 'Pipeline run Successful'
			}
			failure {
				echo 'Pipeline run failed'
			}
		}
}
