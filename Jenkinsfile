pipeline {
    agent any

    stages {
        stage('Pull Code') {
            steps {
                // Clone from GitHub
                git url: 'https://github.com/sagarmagar0709/cicd.git'
                
                // Just to verify it worked
                sh 'ls -l'
            }
        }
    }
}
