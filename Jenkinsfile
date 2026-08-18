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
                sh 'gcc Addition.c -o Addition'
            }
        }

        stage('Run') {
            steps {
                sh './Addition'
            }
        }
    }
}
