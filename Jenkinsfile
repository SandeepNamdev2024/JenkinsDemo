pipeline {
    agent any
    tools {nodejs "npm"}
    
    stages {
        stage('Build') { 
            steps {
                sh 'echo hello' 
            }
        }
        stage('Test') {
            steps {
                sh 'sudo ./jenkins/scripts/test.sh'
            }
        }
    }
}