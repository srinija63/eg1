pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat "javac HelloWorld.java"
                bat "java HelloWorld.java"
            }
        }
        
    }
}
