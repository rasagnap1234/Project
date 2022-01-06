pipeline {
  environment {
      }
  agent any
  stages {
    stage('Cloning Git') {
      steps {
 //       git([url: 'https://github.com/ismailyenigul/hacicenkins.git', branch: 'master', credentialsId: 'ismailyenigul-github-user-token'])
 	checkout scm

      }
    }
    stage('Building image') {
      steps{
        script{
      sh "docker pull ubuntu/nginx"
        }

          }
      }
   
    
    
  }
}
