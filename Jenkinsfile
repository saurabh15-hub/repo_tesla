
pipeline{
    agent any
    stages {
        stage('install dependencies') {
            steps{
                sh 'npm install'
            }
        }
    
        stage('Test'){
            steps{
                sh 'echo "testing application"'
            }
        }
        
        stage('Deploy nodejs application'){
            steps{
                sh 'echo "deploying application"'
            }
        }
    }
    
}
