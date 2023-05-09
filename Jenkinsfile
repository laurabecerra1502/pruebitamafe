@Library('Library1') _

pipeline {
    agent any
    stages {
        stage('Hello World-prueba') {
            steps {
                script {
                    sonarqube.hello(msn: "Lauri")
                }
            }
        }
    }
}