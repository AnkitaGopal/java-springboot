pipeline {
    agent any
    tools {
        maven 'Maven 3.8.6'
    }
    stages {        
        stage('Build') {
            steps {
                echo 'Build'
                sh 'mvn clean package'
            
            }
        }
        stage('Test') {
            steps {
                echo 'Test'
                sh 'mvn Test'
            }
        }
        stage('Sonar-qube') {
            steps {
                echo 'Sonar-qube'      
            }
        }   
        stage('Deploy Dev') {
            steps {
                echo 'Deploy Dev'
            }
        }
    }
}
