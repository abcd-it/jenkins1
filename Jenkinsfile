pipeline {
    agent docker.image('httpd')

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
                echo "Good Day"
            }
        }
    }
}
