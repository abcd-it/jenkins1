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
                docker.image('httpd').withRun('-p 8080:80') {c ->
                sh "curl -i http://${hostIp(c)}:8080/"
                 }
            }
        }
    }
}
