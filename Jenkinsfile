pipeline {
  agent any
  triggers {
    githubPullRequest {}
  }
  stages {
    stage('Set build information'){
      steps{
        script {
         sh "echo 'hi'" 
        }        
      }
    }
  }
  post {
    always {
      cleanWs()
    }
  }
}
