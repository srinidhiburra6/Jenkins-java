pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Compiling Java program'
                sh 'javac HelloWorld.java'
            }
        }

        stage('Test') {
            steps {
                echo 'Executing Java program'
                sh 'java HelloWorld'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Application is ready for deployment'
            }
        }
    }
}
