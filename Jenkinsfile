pipeline {
    agent any
    
    stages {
        stage('Code pull') {
            steps{
                echo "Code has been pulled"
                git branch: 'main', credentialsId: 'mygitcreds', url: 'https://github.com/manikantavasupalli/jenkindemo'
            }
        }

        stage('Build') {
            steps{
                echo "Build has been completed"
            }
        }

        stage('Test') {
            steps{
                echo "Test cases has been executed successfully"
            }
        }
    }
}