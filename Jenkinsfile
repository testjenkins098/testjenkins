pipeline {
    agent { docker 'python:3.5.1' }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
		sh '''
		    mkdir /home/autosrv/jenkins_created
		   '''
            }
        }
    }
}