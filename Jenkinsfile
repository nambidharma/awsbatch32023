def myfn() {
	println "Hi I am coming from myfn code"
}
def fn_with_parsm(a,b) {
	sum = a + b 
	println "add of a & b is ${sum}"
}
pipeline {
	agent any 
	stages {
		stage("working with function") {
			steps {
				script {
					myfn()
					fn_with_parsm(100,200)
				}
			}
		}
	}
}
