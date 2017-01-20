#!groovy
node {
  stage('Build') {
    sh 'make1'
  }

  stage('Test') {
    sh 'make check'
    junit 'reports/**/*.xml'
  }

  stage('Deploy') {
    sh 'make publish'
  }
}
