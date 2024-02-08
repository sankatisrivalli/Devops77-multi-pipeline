pipeline {   
    agent any

    stages {   
        stage('sprint1 branch') { 
            steps { 
               sh 'echo "This is sprint1 branch for testing"' 
            }
        }
     
        stage('test') { 
            steps { 
               sh 'echo "test application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
