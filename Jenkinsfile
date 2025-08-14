pipeline {
    agent any

    stages {
        stage('Unstable Simulation') {
            steps {
                echo 'Marking build as UNSTABLE'
                script {
                    currentBuild.result = 'UNSTABLE'
                }
            }
        }
    }
}
