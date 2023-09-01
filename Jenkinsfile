pipeline {
    agent {label 'slave'} 
    
    stages {
        stage('pull the SCM') {
            steps {
                git 'https://github.com/learnaws288/maven.git'
            }
        }
         stage('build') {
            steps {
                sh "mvn clean package"
            }
        }
    }
}
