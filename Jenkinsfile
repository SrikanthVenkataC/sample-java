pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                java -version
                javac Hello.java
            }
        }
        stage('Run') {
            steps {
                echo 'Run the java code..'
                java Hello
                
            }
        }
        
    }
}
