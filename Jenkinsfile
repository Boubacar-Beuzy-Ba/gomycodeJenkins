pipeline {
    agent any

    tools {
        nodejs 'NODEJS' // Use the name you configured in Global Tool Configuration
    }

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
