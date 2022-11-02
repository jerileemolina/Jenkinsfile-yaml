pipeline {
agent
stages {
    stage('primera etapa') {
    steps {
    script {
        sh release.sh
        while read line; do 
        echo "$line"
        done < release.sh
        
                }
            }
        }
    }
}
