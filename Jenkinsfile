echo "hello from jenkins file"
node {
  def GITREPOREMOTE = "https://github.com/123radhika/Databricks-demo"
  def GITBRANCH     = "main"
  def COPYPATH = "Databricks-demo/test.py"
  def WORKSPACEPATH = "/Shared/jenkins-demo"
  def DBTOKEN ="dapi5d3c8c244e4419f07ddf97e195920544"


  stage('Checkout') {
    git branch: GITBRANCH, url: GITREPOREMOTE
  }

  
  stage('Deploy') {
     pwsh '''
       write-script "hello world"
    '''
    // Use Databricks CLI to deploy notebooks
    //bat 'databricks workspace import_dir ${COPYPATH} ${WORKSPACEPATH}'
       // withCredentials([string(credentialsId: DBTOKEN, variable: 'TOKEN')])"""
  }
}
