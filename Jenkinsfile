pipeline {
	agent any
	tools {
    	maven 'mavenhome'
	}
	stages {
    	stage('Build') {
        	steps {
        	    sh "mvn compile"
        	}
    	}

    	stage("Unit test") {
        	steps {
            	sh "mvn test"
       	}
    }
}
