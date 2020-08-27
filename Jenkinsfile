pipeline {
   agent any
   tools {
      maven 'Maven'
   }
   stages {
       stage("build") {
           steps {
              snDevOpsStep()
               echo "Building" 
                // sh 'mvn clean install -DskipTests'
               sleep 5
           }
       }
       
       
      }
  }
