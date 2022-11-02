pipeline {
agent
stages {
    stage('primera etapa') {
    steps {
    script {
    while read linea;do
    NOMBRE=`echo $linea | cut -d ":" -f1 release.sh`
    VERSION=`echo $linea | cut -d ":" -f2 release.sh`
    echo "$NOMBRE es la $VERSION"
    done
    
                }
            }
        }
    }
}
