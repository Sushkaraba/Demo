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
        stage('Deploy') {
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
