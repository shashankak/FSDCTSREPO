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
            sh 'mvn -B -V -U -e clean package'
        }
        
        stage('Deploy') { 
            steps {
                 echo 'Deploying..'
            }
        }
        
    }
}
