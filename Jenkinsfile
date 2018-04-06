pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('Build') {
            steps {
                sh 'mvn --version'
                sh '''
                   echo "Multiline shell steps works too"
                   ls -lah
                '''
            }
        }
    }
}