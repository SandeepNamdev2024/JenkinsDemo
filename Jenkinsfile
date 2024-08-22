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
                sh "chmod +x -R ${env.WORKSPACE}/jenkins/scripts/test.sh"
                sh './jenkins/scripts/test.sh'
            }
        }
    }
}