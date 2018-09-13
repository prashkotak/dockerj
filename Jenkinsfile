pipeline {
    agent {
        docker { image 'node:7-alpine' 
	         label 'docker'}
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
