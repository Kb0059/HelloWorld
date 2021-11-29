pipeline {
    agent any
    
    
    tools{
    maven 'M3'    
    }
    stages {
        stage('Build') {
            steps {
               bat 'mvn clean'
            }
        }
        stage('Compile') {
            steps {
               bat 'mvn compile'
            }
        }
        stage('Test') {
            steps {
               bat 'mvn test'
            }
        }
        stage('Package') {
            steps {
               bat 'mvn package'
            }
        }
    }
}
