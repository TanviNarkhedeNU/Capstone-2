pipeline {

  agent any
  
  stages {
    stage("Checkout") {
        
          steps {
          checkout([$class: 'GitSCM', branches: [[name: '*/EmotionRecognition-Website']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/TanviNarkhedeNU/Capstone-2.git']]])
          }
     }
    
      stage("build") {
        
          steps {
            
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
