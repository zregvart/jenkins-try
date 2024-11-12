pipeline {
    agent any

    environment {
        PIPELINE_REF = "${currentBuild.dump()}"
    }

    stages {
        stage('Environment') {
            steps {
                sh 'env'
            }
        }
    }
}
