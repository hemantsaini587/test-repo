pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Repository already checked out successfully"
                dir('.') {
                    // for windows use bat
                    // bat 'dir'

                    // for linux use sh

                    sh 'dir'
                }
            }
        }
    }
}
