
pipeline {
    agent any
    stages {
        stage('Read YAML') {
        steps {
        script { 
        datas = readYaml (file: 'release.yaml') 
                }
            }
        }
    }
}