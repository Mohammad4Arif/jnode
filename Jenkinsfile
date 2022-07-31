pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           bat "npm install" 
        }
     }
     
     stage('Test') { 
        steps { 
            echo "testing application..."
        }
      }

         stage("Deploy nodejs application") { 
         steps { 
            echo "deploying application..."
         }

     }
  
   	}

   }
