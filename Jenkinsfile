pipeline{
    agent{
        node{
            label 'master'
        }
    }
    stages{
        stage("Build"){
            steps{
                sh 'echo Hello World'
                sh 'sleep 2'
            }
        }
        stage("Deploy"){
            steps{
                sh 'echo Hello Again'
                sh 'sleep 2'
            }
        }
    }
}
