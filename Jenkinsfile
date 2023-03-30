pipeline {

  agent any
  stages{

     stage('Git Checkout'){
         steps{
               git branch: 'main', url: 'gh repo clone Rngplay123/Jewelofniles'
         
         }
     }
     stage('UNIT Testing'){
         steps{
             sh './gradlew clean build'
         }
     }
  }
}

