@Library('shared-library') _
pipeline {
    agent any
    stages {
        stage('APP_JAVA-INT') {
        steps {
        script {
        data = readYaml file: "release.yaml"
                }
            }
        }
    }
}