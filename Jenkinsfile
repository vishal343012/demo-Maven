pipeline {
    agent  {
        label 'apple'
    }
    tools {
        maven 'maven3'
    }

    stages {
        stage('Git checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/vishal343012/demo-Maven.git'
            }
        }
    
    stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
    stage('Package') {
            steps {
                sh 'mvn package'
            }
        }
    stage('Hello_print3') {
            steps {
                echo 'Hello-World'
            }
        }
    } 
}    
