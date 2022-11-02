pipeline {
    agent any
    stages {
        stage('primera etapa') {
            steps {
                echo "Prueba"
                sh '''
                    file=release.yaml
                    while read -r line; do
                        echo "$line"
                    done < "$file"
                
                '''
            }
        }
    }
}
