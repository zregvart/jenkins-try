pipeline {
    agent any

    environment {
        PIPELINE_REF = "${currentBuild}"
    }

    stages {
        stage('Environment') {
            steps {
                sh 'env'
            }
        }
    }
}
