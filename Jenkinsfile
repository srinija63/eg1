pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git 'https://github.com/srinija63/eg1.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Compiling Java program...'
                bat 'javac ex1/hello.java'
            }
        }
    }
}
