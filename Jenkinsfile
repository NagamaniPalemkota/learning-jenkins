pipeline{
    agent {
        label 'AGENT1'
    }
    options{
        timeout(time: 30,unit: 'MINUTES')
        disableConcurrentBuilds()
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