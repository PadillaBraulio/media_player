pipeline {
    agent any
    options {
        ansiColor('xterm')
        disableConcurrentBuilds()
    }
    stages {
        stage('Checkout') {
          steps {
            checkout scm
          }
        }
        stage('Overwrite artifact') {
          steps {
            sh 'echo hola'
          }
        }
    }
}
