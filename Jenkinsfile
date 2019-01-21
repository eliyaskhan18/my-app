pipeline {
    agent any 
    stages {
        stage('----clean----') { 
            steps {
                sh "mvn clean"
            }
        }
        stage('--Tes---t') { 
            steps {
                sh "mvn test"
            }
        }
        stage('----package-----') { 
            steps {
                sh "mvn package"
            }
        }
    }
}
