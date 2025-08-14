pipeline {
    agent any

    stages {
        stage('Failing Stage') {
            steps {
                echo 'This will fail the build'
                sh 'exit 1'  // Simulates failure
            }
        }
    }
}
