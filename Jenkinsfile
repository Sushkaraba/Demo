pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Build') {
            steps {
                echo 'Hello World'
            }
        }
        stage('D') {
            steps {
                echo 'Hello World'
            }
        }
        stage('D') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post
    {
        always{
            emailext body: 'demo', subject: 'pipeline status', to: 'sushmithamca48@gmail.com'
        }
    }
}
