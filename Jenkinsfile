pipeline {
    agent any

    stage {
        stage('Compile') {
            steps {
                sh 'javac Addition.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Addition'
            }
        }
    }
}
