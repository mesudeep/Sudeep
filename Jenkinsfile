pipeline {
    agent  any
    label 'maven'
    tools {
        jdk 'openjdk8'
        maven '363'
    }
        
    stages {
        stage ('Test') {
            steps {
                sh "mvn clean test"
            }
        }
    }
    
}
