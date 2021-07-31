pipeline {
    agent any
    stages {
        stage('run') {
	    steps {
	        echo 'This is the first run step'
		sh 'python --version'
		sh 'python pipeline.py'
            }
	}
    }
}
