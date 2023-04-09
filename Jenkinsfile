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
                bat 'C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\dotnet-demo\\ConsoleApp.sln --configuration Release'
            }
        }
        
    }
}
