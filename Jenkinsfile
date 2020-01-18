pipeline {
    agent any
	
	triggers {
		pollSCM('H/1 9-18 * * *')
	}
	
    stages {
		stage('Print maven version on on console'){
			steps{
				bat 'mvn -v'
			}
		}
	}
}
