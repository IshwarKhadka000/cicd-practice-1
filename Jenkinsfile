pipeline {
    agent any
    tools{
        jdk 'JAVA'
        maven 'MAVEN'
    }

    stages {
        stage('Hello') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
