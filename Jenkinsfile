pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                sh 'javac Additio.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Addition'
            }
        }
    }
}
