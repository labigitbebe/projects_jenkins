pipeline {
  
  agent any
  
    stages  {
        
      stage("build") {
          steps {
            echo 'building the application'
            }
      }
          
      stage("test") {
        step {
            echo 'testing the application'
          }
      }
       
      stage("deploy") {
        step {
            echo 'deploying the application'
          }
      }
    }
}
