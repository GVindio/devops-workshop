pipeline {
    agent {
        node {
            label 'maven'
        }
        
    }
    

    stages {
        stage('Clone-code') {
            steps {
                git branch: 'main', url: 'https://github.com/GVindio/devops-workshop-3.git'
            }
        }
    }
}