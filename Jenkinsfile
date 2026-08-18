pipeline {
    agent any

    stages {
        stage('Check Files') {
            steps {
                sh 'pwd'
                sh 'ls -la'
            }
        }

        stage('Compile') {
            steps {
                sh 'gcc HelloWorld.c -o HelloWorld'
            }
        }

        stage('Run') {
            steps {
                sh './HelloWorld'
            }
        }
    }
}
