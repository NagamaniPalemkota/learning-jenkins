pipeline{
    agent {
        label 'AGENT1'
    }
    stages{
        stage('Build'){
            steps{
                sh 'echo "This is from Build stage"'
            }

        }
        stage('Test'){
            steps{
                sh 'echo "This is from Test stage"'
            }
        }
        stage('Deploy'){
            steps{
                sh 'echo "This is from Deploy stage"'
            }
        }
    }
}