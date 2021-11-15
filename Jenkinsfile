pipeline {
    agent any
    stages {
       stage("Git Checkout"){
            steps{
                git credentialsId: 'Github_cred', url: 'https://github.com/Noufel6694/Demo.git'
            } 
            }
          
          
          stage('deploy') {
            steps {
                
              echo 'deploying the application...'
            }
          
         }
    }
}
