echo "Hello DB" 
node{
  stage('checkout'){
     
       git branch : 'main', credentialid:'e5a4adda-8639-4cd8-9700-2d68d09bc50c',
       url: 'https://github.com/lpv1990/Databricksdemo.git'
        
  }
  stage('Build'){
     
       bat 'echo Hello Build stage'
        
  }
  stage('Deploy'){
     
       bat 'echo Hello deploy stage'
	   
	   bat 'C:\\Users\\radhika.neelakanta\\AppData\\Local\\Packages\\PythonSoftwareFoundation.Python.3.10_qbz5n2kfra8p0\\LocalCache\\local-packages\\Python310\\Scripts\\databricks.exe workspace import_dir C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\jenkinsdemo\\demoone /Shared/jenkins-demo'
        
  }
}
