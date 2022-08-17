pipeline {
    agent any

    tools {nodejs "node"}
     
    stages {
        stage('Build') {
            steps {
                sh 'npm test'
            }
        }
        stage('Test') {
                    steps {
                        sh './jenkins/scripts/test.sh'
                    }
        }
    }
}