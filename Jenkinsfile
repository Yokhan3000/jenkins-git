pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello Mishka"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
