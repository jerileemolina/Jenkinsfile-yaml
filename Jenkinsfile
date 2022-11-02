pipeline {
agent any
stages {
    stage('primera etapa') {
    steps {
    script {
    while read lineas;do
    echo $lineas;
    done < release.txt
            }
        }
    }
}

}

