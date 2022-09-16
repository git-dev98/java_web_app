pipeline {
	agent any
	stages{
		stage('scan'){
			steps {
			withSonarQubeEnv('sonarqube-8.6.1') {
			sh 'mvn sonar:sonar'
			}
			}
		}
		
	}
}
