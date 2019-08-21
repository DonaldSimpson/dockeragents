pipeline {
    agent {
        dockerfile {
            filename 'Dockerfile'
            args '-v /var/run/docker.sock:/var/run/docker.sock'
        }
    }
    stages {
        stage('Debug steps') {
            steps {
                script {
                    sh 'echo Hi'
                    sh 'printenv'
                    sh 'uname -a'
                    sh 'id'
                }
            }
        }
    }
}
