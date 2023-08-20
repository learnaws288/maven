pipeline {
    agent any
    
    stages {
        stage('SCM pull') {
            steps {
                git 'https://github.com/learnaws288/maven.git'
            }
        }
         stage('Build') {
            steps {
                sh "mvn clean package"
            }
        }
    }
}
