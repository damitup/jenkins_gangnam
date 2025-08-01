pipeline {
    agent any
    stages {
        stage('Prepare'){
            steps {
                git credentialsId: 'MHS',
                    branch: 'main',
                    url: 'https://github.com/damitup/jenkins_gangnam.git'
            }
        }
        stage('test') {
            steps {
                echo 'test stage'
            }
        }
        stage('build') {
            steps {
                echo 'build stage'
            }
        }
        stage('docker build') {
            steps {
                echo 'docker build stage'
            }
        }
    }
}