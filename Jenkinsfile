pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                sh 'java Addition.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Addition'
            }
        }
    }
}
