pipeline{
agent any
stages{
 stage(checkout){
   steps{
     scripts{
       checkout scmGit(branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[credentialsId: 'git-credentials', url: 'https://github.com/ravithala/venu.git']])
       }
      }
     }
    }
  }
