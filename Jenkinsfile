pipeline {
	agent any
	stage("Release") {
            steps {
                	"mvn -B release:prepare"
                	"mvn -B release:perform"
            }
        }
}
