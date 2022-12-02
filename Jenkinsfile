pipeline {

  agent any
  
  stages {
    
    stage("build") {
        
          steps {
            git branch: 'EmotionRecognition-Website', url: 'https://github.com/TanviNarkhedeNU/Capstone-2.git'
            bat 'python app.py'
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
