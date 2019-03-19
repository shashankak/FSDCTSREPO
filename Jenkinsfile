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
                 echo 'Testing..'
            }
            bat('mvn -B -V -U -e clean package')
        }
        
        stage('Deploy') { 
            steps {
                 echo 'Deploying..'
            }
        }
        
    }
}
