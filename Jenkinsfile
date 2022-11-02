pipeline {
agent
stages {
    stage('primera etapa') {
    steps {
    script {
        sh release.sh
        while IFS= read -r line;do
        NOMBRE=`echo $linea | cut -d ":" -f1 release.sh`
        VERSION=`echo $linea | cut -d ":" -f2 release.sh`
        echo '"$NOMBRE" y la versión es "$VERSION"'
        done < release.sh
                }
            }
        }
    }
}
