pipeline {
    agent any
    environment {
        BRANCH_NAME = "${env.BRANCH_NAME}"  // Pass Jenkins branch name to script
    }
    stages {
        stage('Run deploy.sh') {
            steps {
                sh './deploy.sh'
            }
        }
    }
}
