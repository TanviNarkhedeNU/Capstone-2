pipeline {

  agent any
  
  stages {
    
    stage("build") {
        
          steps {
           
            sh 'python app.py'
           }
     }
     stage("test") {
     
        steps {
        echo 'testing..'
        }
     }
     stage("deploy") {
     
        steps {
        echo 'deploying..'
        }
     }
  }
}
