pipeline {
	agent {
                label 'generic'
	}
	stages {
		stage("Run the code!") {
			steps {
				sh """
					python calculator.py
				"""
			} //steps
		} //stage
	} //stages
} //pipeline
