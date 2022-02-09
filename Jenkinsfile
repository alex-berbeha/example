pipeline {
  agent any
  triggers {
    githubPush()
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
