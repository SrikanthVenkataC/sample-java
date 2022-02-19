pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'java -version'
                sh 'javac Hello.java'
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
