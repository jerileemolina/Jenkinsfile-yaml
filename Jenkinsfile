@Library('shared-library') _
pipeline {
    agent any
    stages {
        stage('Read YAML') {
        steps {
        script { 
        datas = readYaml (file: 'release.yaml') 
        echo datas.ear_file.deploy.toString()
                }
            }
        }
    }
}