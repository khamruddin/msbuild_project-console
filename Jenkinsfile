pipeline {
    agent any
    
    stages {
        stage('Checkout Stage') {
            steps {
                echo "checkinot stage"
            }
        }
        stage('Build Stage') {
            steps {
                bat "dotnet clean /ConsoleApp/ConsoleApp/ConsoleApp.csproj"
            }
        }
        
    }
}
