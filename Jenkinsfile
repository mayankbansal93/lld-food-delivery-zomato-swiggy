pipeline {
    agent any
    
    tools {
        jdk 'jdk11'
        maven 'maven3'
    }

    stages {
        stage('Git clone') {
            steps {
                git branch: 'origin/master', url: 'https://github.com/mayankbansal93/lld-food-delivery-zomato-swiggy.git'
            }
        }
        
        stage('mvn validate') {
            steps {
                sh 'mvn validate'
            }
        }
        
        stage('mvn compile') {
            steps {
                sh 'mvn compile'
            }
        }
        
        stage('mvn test') {
            steps {
                sh 'mvn test'
            }
        }
        
        stage('mvn clean package') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
