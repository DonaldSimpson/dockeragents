pipeline {
    agent {
        dockerfile {
            filename 'Dockerfile'
            args '-v /var/run/docker.sock:/var/run/docker.sock'
        }
    }
    stages {
        stage('Prep steps') {
            steps {
                script {
                    sh 'echo Hi'
                    sh 'printenv'
                }
            }
        }
    }
}
