pipeline{
    agent{dockerfile true}
    tools {
        'org.jenkinsci.plugins.docker.commons.tools.DockerTool' 'docker'
    }
    stages{
        stage('source'){
            steps{
                git 'https://github.com/ZhenYu0213/jenkins-robot.git'
            }
        }
        stage('Running Build'){
            steps{
                echo 'Successfully build the docker image and running this command inside it'
            }
        }
    }
}