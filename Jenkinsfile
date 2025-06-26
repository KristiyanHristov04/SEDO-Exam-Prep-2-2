pipeline {
    agent any

    stages {
        stage('Build') {
            when {
                branch 'main'
            }
            steps {
                echo 'Build .NET Application'
                bat 'dotnet build'
            }
        }
        stage('Execute Tests') {
            when {
                branch 'main'
            }
            steps {
                echo 'Run both Unit and Integration Tests'
                bat 'dotnet test'
            }
        }
    }
}