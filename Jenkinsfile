pipeline {
	agent any 
	stages {
		stage("working with loops") {
			steps {
				script {
					a=1
					while ( a <= 10 ){
						println "a value is ${a}"
						a = a + 1
					}
					// working with for loop 
					for(i=1;i<=10;i++) {
						println "my i value is ${i}"
					}
					// for loop other syntax
					lis=[10,20,30,40]
					for(i in lis){
						println "my lis ele value is ${i}"
					}
				}
			}
		}
	}
}
