pipeline {

   agent any 
   stages {
   
     stage("build develop") {
       when {
          branch "develop"
       }
       steps {
          echo "building development branch"
       }
     
     }
     stage("build master") {
       when {
          branch "master"
       }
       steps {
          echo "building master branch"
       }
     
     }
   
   }

}
