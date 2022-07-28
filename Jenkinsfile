pipeline{
    agent any
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
