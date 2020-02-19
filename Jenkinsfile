pipeline {
	agent any
	stages {
		stage("Release") {
            		steps {
                		"mvn -B release:prepare"
                		"mvn -B release:perform"
            		}
        	}
	}
}
