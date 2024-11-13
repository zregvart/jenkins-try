pipeline {
    agent any

    environment {
        PIPELINE_PATH = "${rhtap.env().pipeline_path}"
        RUN_CAUSES = "${rhtap.env().run_causes}"
        START_TIME = "${rhtap.env().start_time}"
    }

    stages {
        stage('Environment') {
            steps {
                sh 'env'
            }
        }
    }
}
