pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World - Dan edit to trigger webhook"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
