pipeline {
    agent any
    
    stages {
        stage('Checkout Stage') {
            steps {
                url: 'https://github.com/khamruddin/msbuild_project-console.git'
            }
        }
        stage('Build Stage') {
            steps {
                bat 'C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\dotnet-demo\\HelloWorld.sln --configuration Release'
            }
        }
        
    }
}
