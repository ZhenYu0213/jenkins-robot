pipeline{
    agent {
        docker { image 'python:3' }
    }
    stages {
        stage('build') {
            steps {
                sh 'python test.py'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
