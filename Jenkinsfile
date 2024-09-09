pipeline {
  agent any
  stages {
    stage('build-images') {
      steps {
        sh 'echo hello world'
      }
    }

    stage('test') {
      parallel {
        stage('test-unit') {
          steps {
            sh 'echo hello world'
          }
        }

        stage('test-code') {
          steps {
            sh 'echo hello world'
          }
        }

      }
    }

    stage('push') {
      parallel {
        stage('push') {
          steps {
            sh 'echo hello world'
          }
        }

        stage('update-tag') {
          steps {
            sh 'echo hello world'
          }
        }

      }
    }

  }
}