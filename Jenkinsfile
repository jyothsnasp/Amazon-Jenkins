pipeline {
    agent any
    
    tools {
        maven 'Maven'
    }
    stages {
        stage('Clone') {
            steps {
                git branch:'main' , url: 'https://github.com/jyothsnasp/Amazon-Jenkins.git'
            }
            }
        stage('build') {
            steps {
                sh 'mvn clean install'
            }    
        }
    }
}
