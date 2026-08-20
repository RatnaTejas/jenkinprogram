pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                sh 'javac aaddition.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Addition'
            }
        }
    }
}
