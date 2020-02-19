pipeline {
	agent any
	stages {
		stage("Release") {
            		steps {
                		bat "mvn -Dmaven.javadoc.skip=true -B release:prepare"
                		bat "mvn -Dmaven.javadoc.skip=true -B release:perform"
			}
        	}
	}
}
