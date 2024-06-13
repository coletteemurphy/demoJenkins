pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                echo "in build stage" 
                sh 'ls -al'  
            }      
        }
        stage('Test'){
            steps{
                echo "in test stage "
            }    
        }
        stage('Deploy'){
            steps{
                echo "in deploy stage "
                sh 'sh ./deploy.sh'
            }    
        }
    }
}