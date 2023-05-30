pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                    sh label: 'run-some-script',
                        returnStatus: true,
                        script: '''
                        echo WE ARE DOING FINE
                        '''
            }
        }
    }
}