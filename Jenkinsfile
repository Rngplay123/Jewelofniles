pipeline {

  agent any
  stages{

     stage('Git Checkout'){
         steps{
               git branch: 'main', url: 'https://github.com/Rngplay123/Jewelofniles.git'
         
         }
     }
     stage('UNIT Testing'){
         steps{
             sh './gradlew clean build'
         }
     }
         
  }
}

