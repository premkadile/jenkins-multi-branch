pipeline { 
  
   agent any
   stages {
   triggers {
        cron('* * * * *')
    }
   
     stage('Install Dependencies') { 
        steps { 
           sh 'echo "cronadded in mainjenkinsfile"' 
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
