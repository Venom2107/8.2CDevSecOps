pipeline {
    agent any

    stages {
        stage('Check Node') {
            steps {
                bat 'where node'
                bat 'where npm'
                bat 'node -v'
                bat 'npm -v'
            }
        }
    }
}
