pipeline {
    agent any
        stages {
            stage ('build') {
                steps {
                    sh 'echo "starting steps"'
                    sh '''
                        echo "multiline command"
                        ls -lah
                        pwd
                        '''
                }
            }
        }
}
