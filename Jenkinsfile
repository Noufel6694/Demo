pipeline {
    agent any
    stages {
       stage("Git Checkout"){
            steps{
                git credentialsId: 'github', url: 'https://github.com/Noufel6694/Demo.git'
            } 
            }
          stage('test') {
            steps {
              echo 'testing the application...'
            } 
              
            }
          
          stage('deploy') {
            steps {
                
              echo 'deploying the application...'
            }
          
         }
    }
}
