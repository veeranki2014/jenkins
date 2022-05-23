pipeline {
    agent {
        node { label 'workstation' }
    }
    stages {
        stage ('ONE'){
            steps{
            sh 'echo world - workstation-1'
            }
        }
        stage ('TWO'){
                    steps{
                    sh 'echo world - workstation -2'
                    }
                }
    }

}