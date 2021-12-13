pipeline {
    agent any

    stages {
        stage('build') {
            steps {
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
                docker.image('httpd')
            }
        }
    }
}
