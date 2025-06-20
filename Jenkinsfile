pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                bat 'dotnet build'
            }
        }

        stage('Run Tests') {
            steps {
                echo 'Running tests...'
                bat 'dotnet test'
            }
            
        }
    }
}