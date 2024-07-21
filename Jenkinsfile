pipeline{
  agent any
  stages{
    stage('fetch code'){
      steps{
      git branch: 'main', url: 'https://github.com/vskartheek/practice.git'
          }
      }
    stage('Install web and deploy'){
      steps{
            sh 'sh deplyment.sh'
          }
      }
  }

}
