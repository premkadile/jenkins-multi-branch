pipeline { 
  
   agent any
   triggers {
        cron('* * * * *')
    }
   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'echo "checking build perodic"' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
