<<<<<<< HEAD
pipeline {
    agent {
        dockerfile {
            filename 'Dockerfile'
            args '-v /var/run/docker.sock:/var/run/docker.sock'
        }
    }


    options {
        // disableConcurrentBuilds()
        // parallelsAlwaysFailFast()
        timestamps()
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
=======
pipeline {
    agent {
        dockerfile {
            filename 'Dockerfile'
            args '-v /var/run/docker.sock:/var/run/docker.sock'
        }
    }


    options {
        disableConcurrentBuilds()
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
>>>>>>> 8fb7d66e41f3df42224f827836ad28ea71b5f4b4
