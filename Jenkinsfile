pipeline {
    agent any
	
	triggers {
		pollSCM('H/1 9-18 * * *')
	}
	
    stages {
		stage('Print maven version'){
			steps{
				bat 'mvn -v'
			}
		}
	}
}
