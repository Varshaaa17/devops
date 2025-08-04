pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'Hello jenkins!!'
                bat 'javac Hello.java'
                bat 'java Hello'
            }
        }
    }
}
