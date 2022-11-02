pipeline {
agent
stages {
    stage('primera etapa') {
    steps {
    script {
       sh release.sh
       for line in $(release.sh);do
       echo "$line"
       done
        
                }
            }
        }
    }
}
