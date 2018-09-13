pipeline {
    agent { dockerfile true 
            label 'docker'
          }
    stages {
        stage('Test') {
            steps {
                sh 'httpd --version'
               
            }
        }
    }
}
