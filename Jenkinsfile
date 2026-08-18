pipeline {
    agent any

    stages {
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
