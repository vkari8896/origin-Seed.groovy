pipeline {
    
 agent any
    
 stages {
       
  stage('Folder creation') {
     
       steps {

sh 'ls -l'
    
 dir ('ORIGIN') {
       
  writeFile file:'dummy', text:''
    }
  
  sh 'ls -l'
}


            }
        }
        
    }
