pipeline {
    
    agent any
    
    stages {
        
         stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                bat('mvn -B -V -U -e clean package')
                 echo 'Testing..'
            }
            
        }
        
        stage('Deploy') { 
            steps {
                 echo 'Deploying..'
            }
        }
        
    }
}
