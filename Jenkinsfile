pipeline {
    agent any
    stages {
        stage('Build C Program') {
            steps {
                sh 'gcc hello.c -o hello'
            }
        }
        stage('Run C Program') {
            steps {
                sh './hello'
            }
        }
    }
}
