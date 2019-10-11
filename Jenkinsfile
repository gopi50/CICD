node{
  stage('SCM Checkout'){
     git 'https://github.com/gopi50/CICD'
   }
   stage('Compile-Package'){
     //get maven home path
     def mvnHome = tool name: 'Maven3.6.1', type: 'maven'
     sh "${mvnHome}/bin/mvn package"
  }

}
