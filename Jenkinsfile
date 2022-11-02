@Library('shared-library') _
pipeline {
    agent any
    stages {
        stage(`'Read YAML') {{
            script{ datas = readYaml (file: 'release.yml') }
            echo datas.ear_file.deploy.toString()
            }
        }
    }
}