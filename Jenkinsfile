pipeline {
 agent any 
     stages ('--clean--') {
         steps {
            sh "mvn clean"
            
          }
          }
          stage('--test--') {
           steps {
            sh  "mvn test"
          }
          }
          stage('--package--') {
           steps {
            sh "mvn package"
            }
            }
            }
            
            
          
          
      
