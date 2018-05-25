pipeline {
    agent any

    stages {
        stage('Build') {
            tools {
              maven "maven 3.5.3"  
              jdk "jdk 1.8.172"
            }
            steps {
                echo 'Building..'
                sh 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}