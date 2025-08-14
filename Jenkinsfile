pipeline {
    agent any

    stages {
        stage('Abort Simulation') {
            steps {
                echo 'Aborting the build...'
                script {
                    currentBuild.result = 'ABORTED'
                    error('Aborting the build intentionally')
                }
            }
        }
    }
}
