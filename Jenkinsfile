properties([pipelineTriggers([githubPush()])])

node {git url: 'https://github.com/amirmughal0303/deploy_react_cicd.git', branch: 'main'}
pipeline{
    agent none
    stages {
        stage("build"){
                
            steps {
                echo 'building the application...'

            }

            }
        stage("test"){
                
            steps {
                echo 'testing the application...'

            }

            }
        stage("deploy"){
                
            steps {
                echo 'deploy the application...'
                build job: 'deploy_job'

            }

            }
        }
    
}
