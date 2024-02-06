echo "Hello DB" 
node{
  stage('checkout'){
     
       git branch : 'main', credentialid:'29f7e6d5-5471-4877-a941-54c3c759f0ad',
       url: 'https://github.com/123radhika/Databricks-demo.git'
        
  }
  stage('Build'){
     
       bat 'echo Hello Build stage'
        
  }
  stage('Deploy'){
     
       bat 'echo Hello deploy stage'
	   
       bat 'C:\\Users\\radhika.neelakanta\\AppData\\Local\\Packages\\PythonSoftwareFoundation.Python.3.10_qbz5n2kfra8p0\\LocalCache\\local-packages\\Python310\\Scripts\\databricks.exe workspace import_dir C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\Databricks-demo\\Jenkins-test /Shared/jenkins-demo'
        
  }
}
