pipeline {   
    agent any

    stages {   
        stage('Development branch') { 
            steps { 
               sh 'echo "This is Development branch"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "sprint1 application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
