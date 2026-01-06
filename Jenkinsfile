/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'node:trixie-slim' } }
    stages {
        stage('build') {
            steps {
                sh 'node -v'
            }
        }
    }
}
