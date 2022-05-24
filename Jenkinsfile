pipeline {
    /* agent {
        //node { label 'workstation' }
        //label 'JAVA'
        none
    } */
    agent none
    stages {
        stage ('ONE'){
           agent{
            label 'MASTER'
           }
            steps{
            sh 'echo world - workstation-1'
            }
        }
        stage ('TWO'){
            agent{
                        label 'JAVA'
                       }
                    steps{
                    sh 'echo world - workstation -2'
                    }
                }
    }

}