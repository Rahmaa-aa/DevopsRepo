pipeline {
    agent any
    tools {
        maven "M2_HOME"
        jdk "JAVA_HOME"
    }
    stages {
        stage("Maven Version") {
            steps {
                sh "mvn -version"
            }
        }
    }
}