pipeline {
    agent any
    tools {nodejs "npm"}
    
    stages {
        stage('Build') { 
            steps {
                sh 'usr/bin/npm install' 
            }
        }
    }
}