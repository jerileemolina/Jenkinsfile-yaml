
pipeline {
agent
stages {
    stage('primera etapa') {
    steps {
    script {
        sh release.sh
    (for LINEA in `release.sh`) //LINEA guarda el resultado
    do
    NOMBRE=`echo $LINEA | cut -d ":" -f1` //Extrae nombre
    VERSION=`echo $LINEA | cut -d ":" -f2` //Extrae version
    echo "$NOMBRE es la $version" //Muestra resultado
    done
            }
        }
    }
}



}
