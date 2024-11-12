pipeline {
    agent any

    environment {
        PIPELINE_REF = "${currentBuild.buildCauses}"
    }

    stages {
        stage('Environment') {
            steps {
                sh 'env'
            }
        }
    }
}
