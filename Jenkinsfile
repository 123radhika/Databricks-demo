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
                bat 'C:\\Users\\radhika.neelakanta\\AppData\\Local\\Packages\\PythonSoftwareFoundation.Python.3.10_qbz5n2kfra8p0\\LocalCache\\local-packages\\Python310\\Scripts\\databricks.exe workspace import_dir C:\\Users\\radhika.neelakanta\\Downloads\\test-project /Shared/jenkins-demo'
            }
        }
    }
}
    
