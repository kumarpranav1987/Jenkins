pipeline {
	agent any
	stages {
		stage("Release") {
            		steps {
                		bat "mvn -B release:prepare"
                		bat "mvn -B release:perform"
			}
        	}
	}
}
