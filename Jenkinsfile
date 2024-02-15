pipeline {
    agent any
       
    }
    stages {
        stage('Build') {
            steps {
                // Example steps to build your project
                sh 'mvn clean package'
            }
        } 
        
        stage('Test') {
            steps {
                // Example steps to run tests
                sh 'mvn test'
            }
        }
        stage('Deploy') {
            steps {
                // Example steps to deploy your application
                
            }
        }
    }
}