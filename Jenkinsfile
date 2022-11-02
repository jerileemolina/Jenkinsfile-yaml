pipeline {
agent
stages {
    stage('primera etapa') {
    steps {
    script {
        sh release.sh
    while read linea; //LINEA guarda el resultado
    do
    NOMBRE=`echo $linea | cut -d ":" -f1 release.sh` //Extrae nombre
    VERSION=`echo $linea | cut -d ":" -f2 release.sh` //Extrae version
    echo "$NOMBRE es la $VERSION" //Muestra resultado
    done
    
                }
            }
        }
    }
}
