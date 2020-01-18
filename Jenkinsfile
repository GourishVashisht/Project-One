pipeline {
    agent any
	
	triggers {
		pollSCM('H/1 9-18 * * 1-5')
	}
	
    stages {
		stage('Print maven version'){
			steps{
				bat 'mvn -v'
			}
		}
	}
}
