pipeline {
    agent any

   
    stages {
        stage {
            steps('Build') {
                echo 'Build .NET Application'
                bat 'dotnet build'
            }
        }
        stage {
            steps('Execute Tests') {
                echo 'Run both Unit and Integration Tests'
                bat 'dotnet test'
            }
        }
    }
}