pipeline {
    agent any

    environment {
        PIPELINE_PATH = "${rhtap.env().pipeline_path}"
        RUN_CAUSES = "${rhtap.env().run_causes}"
    }

    stages {
        stage('Environment') {
            steps {
                sh 'env'
            }
        }
    }
}
