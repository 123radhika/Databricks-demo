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
                bat'databricks workspace import_dir C:\\Users\\radhika.neelakanta\\Downloads\\s3 static website acg /Shared/jenkins-demo'
            }
        }
    }
}
