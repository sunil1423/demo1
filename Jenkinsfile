pipeline{
    agent any
    stages{
        stage('Building'){
            steps{
                bat 'mvn install'
                
            }
        }
       
        stage('execute'){
            steps{
                bat 'java -jar target/MavenProject-v1.jar'
            }
        }
        
    }
}
