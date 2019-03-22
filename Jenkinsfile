pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                junit '**/target/*.xml' 
            }
        }
    }
}