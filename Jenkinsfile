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
