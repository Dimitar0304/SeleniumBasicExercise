pipeline{
    agent any
    stages{
        stage("BuildApp")
        {
            steps{
                
             bat 'dotnet build'
            }
        }
        stage("run tests")
        {
            steps{
                bat 'dotnet test'
            }
        }
    
    }
}