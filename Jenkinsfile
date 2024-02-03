echo "hello from jenkins file"
node {
  def GITREPOREMOTE = "https://github.com/123radhika/Databricks-demo"
  def GITBRANCH     = "main"
  def COPYPATH = "Databricks-demo/test.py"
  def WORKSPACEPATH = "/Shared/jenkins-demo"
 
  stage('Deploy') {
  sh """#!/bin/bash
        # Use Databricks CLI to deploy notebooks
        databricks workspace import_dir ${COPYPATH}  ${WORKSPACEPATH}

     """
  //withCredentials([string(credentialsId: DBTOKEN, variable: 'TOKEN')])
  
  }
}
