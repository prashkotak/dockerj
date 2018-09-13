pipeline {
	agent {
		dockerfile {
        filename 'Dockerfile'
		label 'docker'
        
		}	
	}
    stages {
        stage('Test') {
            steps {
                sh 'httpd --version'
		sh 'docker run -dit --name my-apache-app -p 8080:80 -v /tmp/:/usr/local/apache2/htdocs/ httpd'    
            }
        }
    }
}
