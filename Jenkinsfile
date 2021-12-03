pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Build'
            }
        }
        stage('Test') {
            steps {
                echo 'Test'
            }
        }
        stage('Deploye') {
            steps {
                echo 'Deploye'
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
