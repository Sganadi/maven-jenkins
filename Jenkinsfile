pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Application'
            }
        }
         stage('Test') {
            steps {
                echo 'Testing Application'
            }
        }
         stage('Deploy') {
            steps {
                echo 'Deploying Application'
            }
        }
        
        
        
        
        
        
        
    }
    post {
        always{
            emailext body: 'Summary', subject: 'PipeLine Status', to: 'saikrishnaganadi123@gmail.com'
        }
    }
}
