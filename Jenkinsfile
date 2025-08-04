pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
            git branch: 'main', url: 'https://github.com/srinija63/eg1.git'
        }
    }


        stage('Build') {
            steps {
                echo 'Compiling Java program...'
                bat 'javac hello.java'
            }
        }

        stage('Test') {
            steps {
                echo 'Running Hello World...'
                bat 'java HelloWorld'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Simulating deployment...'
            }
        }
    }
}
