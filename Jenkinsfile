pipeline {
    agent any

    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello from Stage 1!'

                sh '''
                #!/bin/bash
                sleep 10
                echo 'This is Linux command'

                '''
            }
        }

        stage('Stage 2') {
            steps {
                echo 'Hello from Stage 2!'
            }
        }
    }
}