pipeline {
    agent { docker { image 'python:3.10.1-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version;date' > /tmp/data1
                sh 'uptime' >> /tmp/data1
            }
        }
    }
}
