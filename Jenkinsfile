pipeline {
    agent any

    stages {
        stage ('Init') {
            steps {
                echo 'Gathering information'
                echo 'Preparing for build'
            }
        }
        stage ('Build') {
            steps {
                echo 'Building .. .'
            }
        }
        stage ('Deploy') {
            steps {
                echo 'Deploying to staging'
                echo 'Deploying to prod'
            }
        }
    }
}