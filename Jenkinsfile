pipeline {
    agent any

    environment {
        PIPELINE_REF = "${rhtap.env().pipeline_path}"
    }

    stages {
        stage('Environment') {
            steps {
                sh 'env'
            }
        }
    }
}
