pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Building'
            }
        }
        stage('Test') {
            steps {
                echo 'Tested'
            }
        }
        stage('Deploye') {
            steps {
                echo 'Deployed'
            }
        }
    }
    post{
        always{
            echo 'Always'
        }
        success{
            echo 'Success'
        }
        failure{
            echo 'Failure'
        }
    }
}
