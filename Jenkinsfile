pipeline {
    agent {
        docker { 
            image 'maven:3.8.4' 
        }
    }
    stages {
        stage('test') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
