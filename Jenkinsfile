pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build .NET Application'
                bat 'dotnet build'
            }
        }
        stage('Execute Tests') {
            steps {
                echo 'Run both Unit and Integration Tests'
                bat 'dotnet test'
            }
        }
    }
}