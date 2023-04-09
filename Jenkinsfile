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
               // bat "dotnet clean /ConsoleApp/ConsoleApp/ConsoleApp.csproj"
                bat "msbuild.exe \"${WORKSPACE}\dotnet-demo\ConsoleApp.sln\" -t:clean -t:build -restore /property:Configuration=Release -p:RestorePackagesConfig=true"
            }
        }
        
    }
}
