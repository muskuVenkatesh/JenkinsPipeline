pipeline {
    agent any

    stages {

        stage('Hello') {
            steps {
                echo 'Hello Venkatesh!'
            }
        }

        stage('System Info') {
            steps {
                sh 'pwd'
                sh 'whoami'
                sh 'date'
            }
        }

        stage('Success') {
            steps {
                echo 'My first pipeline executed successfully'
            }
        }
    }
}