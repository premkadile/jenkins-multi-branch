pipeline { 
  
   agent any
   stages {
   triggers {
        cron('* * * * *')
    }
   
     stage('Install Dependencies') { 
        steps { 
           sh 'echo "test1"' 
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
