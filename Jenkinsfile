pipeline {
    agent any
    stages {
        stage('primera etapa') {
            steps {
                echo "Prueba"
                sh '''
                    file=/Documentos/release.yaml
                    while read -r line; do
                        echo "$line"
                    done < "$file"
                '''
            }
        }
    }
}
