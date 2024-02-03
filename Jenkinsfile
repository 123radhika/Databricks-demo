echo "hello from jenkins file"
node {
  def GITREPOREMOTE = "https://github.com/123radhika/Databricks-demo"
  def GITBRANCH     = "main"
  def COPYPATH = "Databricks-demo/test.py"
  def WORKSPACEPATH = "/Shared/jenkins-demo"
  
  stage('Checkout') {
    git branch: GITBRANCH, url: GITREPOREMOTE
  }

  stage('Deploy') {
    echo "hello deploy"
  //withCredentials([string(credentialsId: DBTOKEN, variable: 'TOKEN')])
  
  }
}
