pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                sh "python --version"
                echo 'Hello World'
            }
        }
        stage('test') {
            steps {
                echo 'Hello test'
            }
        }
        stage('deploy') {
            steps {
                echo 'Hello deploy'
            }
        }
    }
}
