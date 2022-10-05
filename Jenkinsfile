pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git "https://github.com/coralogix-resources/java-rest-api-calculator.git"
                sh "mvn clean compile"
            }
        }
    }
}
