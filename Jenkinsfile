pipeline {
    agent any

    stages {
        stage {
            steps {
                echo 'Build .NET Application'
                bat 'dotnet build'
            }
        }
        stage {
            steps {
                echo 'Run both Unit and Integration Tests'
                bat 'dotnet test'
            }
        }
    }
}