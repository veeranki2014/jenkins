pipeline {
    agent {
        //node { label 'workstation' }
        label 'JAVA'
    }
    stages {
        stage ('ONE'){
            steps{
            sh ' world - workstation-1'
            }
        }
        stage ('TWO'){
                    steps{
                    sh 'echo world - workstation -2'
                    }
                }
    }

}