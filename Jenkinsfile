pipeline{
    agent any
    
    stages{
        
        stage("Git Clone Step"){
            steps{
                echo "Cloning repo..."
                git branch: 'dev', url: 'https://github.com/rohantambat/java_app.git'
            }
        }
    }
}
