pipeline {
	agent any 
	stages {
		stage("working with variables") {
			steps {
				script {
					var1=10
					var2="dvs technologies"
					println "myvar1 value is ${var1} and myvar2 value is ${var2}"
					println "my workspace is ${WORKSPACE}"
					println "my build no is ${BUILD_NUMBER}"
				}
			}
		}
	}
}
