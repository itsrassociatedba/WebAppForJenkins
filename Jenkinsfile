pipeline {
    agent any
    tools {
        maven 'Maven 3.9.0'
    }
    stages {
        stage('Clean and Install') {
            steps {
                sh 'mvn clean install'
            }
        }
        stage('Package') {
            steps {
                sh 'mvn package'
            }
        } 
    }
}
