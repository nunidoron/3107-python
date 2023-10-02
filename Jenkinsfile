properties([pipelineTriggers([pollSCM('* * * * *')])])
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'python main.py'
            }
        }
        stage('Hello2') {
            steps {
                sh 'python main.py'
            }
        }
    }
}
