pipeline {
   agent any
   stages {
       stage('1-Build Code') {
           steps {
               echo "Building Artifact"
               echo "testingcode"
           }
       }
      stage('2-Deploy Code') {
          steps {
               echo "Deploying Code"
          }
      }
      stage ('3-testing code' ){
        steps{
            sh 'lscpu'
        }
      }
   }
}

  

