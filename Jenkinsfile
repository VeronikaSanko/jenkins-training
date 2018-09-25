node{
   stage('SCM Checkout'){
     git 'https://github.com/VeronikaSanko/jenkins-training'
   }
   stage('Compile-Package'){
      // Get maven home path
      def mvnHome =  tool name: 'maven-3', type: 'maven'   
      sh "${mvnHome}/bin/mvn package"
   }
}
