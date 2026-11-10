// Declarative Pipeline
pipeline{
    agent
        node{
            label 'ROBOSHOP'
        }
    stages{
        stage('Build'){
            steps{
                sh """
                    echo 'Building...'
                """
            }
        }
        stage('Test'){
            steps{
                sh """
                    echo 'Testing...'
                """
            }
        }
        stage('Deploy'){
            steps{
                sh """
                    echo 'Deploying...'
                """ 
            }
        }
    }

    // POST BUILD
    post{
        always{
            echo 'This will always run'
        }
    }
}