pipeline {
    agent any
    stages {
        stage('Compile'){
            steps{
                bat 'javac BankService.java'
            }
        }
        
        stage('Run'){
            steps{
                bat 'java BankService'
            }
        }
    }
}
