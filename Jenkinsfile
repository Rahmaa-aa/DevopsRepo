pipeline {
    agent any
    tools {
        maven "MAVEN"
        jdk "JDK"
    }
    stages {
        stage("MAVN") {
            steps {
                sh "mvn -version"
            }
        }
    }
}