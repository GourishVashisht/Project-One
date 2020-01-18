pipeline {
    agent any
	
	triggers {
		pollSCM('H/2 9-18 * * *')
	}
	
	parameters {
	    string(name: 'STRING_VALUE', defaultValue: 'Jenkins', description: 'Any string value ?')
    }
	
    stages {
		stage('Print maven version'){
			steps{
				echo '${STRING_VALUE}'
				bat 'mvn -v'
			}
		}
	}
}
