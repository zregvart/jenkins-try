pipeline {
    agent any

    environment {
        PIPELINE_PATH = "${rhtap.env().pipeline_path}"
        PIPELINE_REV = "${rhtap.env().pipeline_rev}"
    }

    stages {
        stage('Environment') {
            steps {
                sh 'env'
            }
        }
    }
}
