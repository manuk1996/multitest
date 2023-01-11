pipeline {
    agent any

    stages {
        stage('SCM checkout') {
            steps {
                echo 'this is the checkout stage'
                sh 'sleep 5'
            }
        }
         stage('build') {
            steps {
                echo 'this is the build stage'
                sh 'sleep 5'
            }
        }
        stage('push') {
            steps {
                echo 'this is the artifactory stage'
                sh 'sleep 5'
            }
        }
         stage('deploy') {
            steps {
                echo 'this is the deploy stage'
                sh 'sleep 5'
            }
        }
         stage('test') {
            steps {
                echo 'this is the test stage'
                sh 'sleep 5'
            }
        }
        stage('realease') {
            steps {
                echo 'this is the realease stage'
                sh 'sleep 5'
            }
        }
    }
}
