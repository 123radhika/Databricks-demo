pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
                bat 'echo Hello Build stage'
                bat 'mkdir C:\\Db-jenkins-tesst'
            }
        }
        stage ('Test') {
            steps {
                bat 'echo hello Test stage'
            }
        }
    }
}
