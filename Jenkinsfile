pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'echo "install dependencies..."' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing the application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying the application..."'
         }

     }
  
   	}

   }
