pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'docker --version'
                sh """ 
                docker images
                """
            }
        }
        stage('Run') {
            steps {
                echo 'Run the java code.. with a GitHub webhook'
                sh 'java Hello'
                
            }
        }
        
    }
}
