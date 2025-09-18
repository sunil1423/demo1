pipeline{
    agent any
    stages{
        stage('Building'){
            steps{
                sh 'mvn install'
                
            }
        }
       
        stage('execute'){
            steps{
                sh 'java -jar target/MavenProject-v1.jar'
            }
        }
        
    }
}

