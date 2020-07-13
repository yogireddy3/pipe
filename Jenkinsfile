
pipeline{
    agent any
    tools {
        maven 'maven:3'
    }
    stages{

        stage('Maven Build'){
            steps{
                sh 'mvn clean package'
            }
        }
     
        }
    }
