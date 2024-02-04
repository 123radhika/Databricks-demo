pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
                bat 'echo Hello Build stage'
                //bat 'mkdir C:\\Db-jenkins-tesst'
            }
        }
        stage ('Deploy') {
            steps {
                bat 'echo hello Deploy stage'
                bat 'C:\\Users\\radhika.neelakanta\\Downloads\\databricks-import.bat C:\\Users\\radhika.neelakanta\\Downloads\\operr.txt 2>&1'
            }
        }
    }
}
    
