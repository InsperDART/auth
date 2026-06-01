pipeline {
    agent any
    tools {
        maven 'Maven'
    }
    stages {
        stage('Install') {
            steps {
                sh 'mvn -B -DskipTests clean install'
            }
        }
    }
}