node {
    stage('Clone') {
       git 'https://github.com/cherif63/jenkins-helloworld.git'
    }
    stage('Build') {
    sh 'javac Main.java'
    }
    stage('Run') {
    sh  'java Main'
    }
   }
