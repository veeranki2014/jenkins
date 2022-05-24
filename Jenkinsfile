/*
pipeline {
     */
/* agent {
        //node { label 'workstation' }
        //label 'JAVA'
        none
    } *//*

    //agent none - doesn't work with post.so enable "agent any"
    agent any
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

    post {
        always{
        sh 'echo Post Steps'
        }
    }

} */

pipeline{
    agent any
    environment {
        DEMO_URL = google.com
    }

    stages{
        stage ('ANKA'){
          steps {
            sh 'echo ${DEMO_URL}'
          }
        }
    }

}
