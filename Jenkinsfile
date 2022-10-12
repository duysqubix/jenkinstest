pipeline {
    agent { docker { image 'python:3.10.7-alphine' } }
    stages {
        stage('build'){
            steps{
                sh 'python -version'
            }
        }
    }
}
