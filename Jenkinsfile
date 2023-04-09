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
                bat 'C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\dotnet-demo\\HelloWorld.sln --configuration Release'
            }
        }
        
    }
}
