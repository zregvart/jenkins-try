library identifier: 'RHTAP_Jenkins@main', retriever: modernSCM(
  [$class: 'GitSCMSource',
   remote: 'https://github.com/zregvart/tssc-sample-jenkins.git'])

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
