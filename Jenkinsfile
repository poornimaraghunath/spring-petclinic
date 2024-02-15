pipeline {
    agent{
      any {
            image 'maven:3.8.4' // specify the Maven Docker image
            args '-v /root/.m2:/root/.m2' // mount Maven settings and local repository 
        }  
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