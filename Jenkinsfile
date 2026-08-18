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
                sh 'gcc addition.c -o addition'
            }
        }

        stage('Run') {
            steps {
                sh './addition'
            }
        }
    }
}
