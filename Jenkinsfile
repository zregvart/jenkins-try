pipeline {
    agent any

    environment {
        PIPELINE_REF = "${new groovy.json.JsonBuilder(currentBuild).toPrettyString()}"
    }

    stages {
        stage('Environment') {
            steps {
                sh 'env'
            }
        }
    }
}
