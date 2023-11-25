pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    echo 'Building the Angular project'
                    sh 'npm install'
                    sh 'npm build'
                }
            }
        }
    }
}
