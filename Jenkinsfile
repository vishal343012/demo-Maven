 pipeline {
    agent any

    stages {
        stage('git checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/vishal343012/demo-Maven.git'
            }
        }
    
        stage('compile') {
            steps {
                sh "mvn compile"
        }    
   }
   stage('Hello') {
            steps {
                echo "Hello world-3"
        }    
   }
}
}
