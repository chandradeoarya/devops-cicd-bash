pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo "Learn DevOps"
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
        }
    }
}
