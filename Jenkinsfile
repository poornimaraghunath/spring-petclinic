pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Example steps to build your project
                sh 'cd spring-petclinic && mvn clean package'
            }
        } 
        
        stage('Test') {
            steps {
                // Example steps to run tests
                sh 'mvn test'
            }
        }
        
    }

}