pipeline {
  agent any
  stages {
    stage('Code Quality') {
      steps {
        sh 'sh echo checking code quality'
      }
    }

    stage('Unit Tests') {
      steps {
        sh 'sh echo Testing the Applications'
      }
    }

    stage('Build') {
      steps {
        sh 'sh echo Creating application Package'
      }
    }

    stage('Delivery') {
      steps {
        sh 'sh echo Uploading the artifact to a repository'
      }
    }

    stage('Deploy') {
      steps {
        sh 'sh echo Deploying the Application'
      }
    }

  }
}