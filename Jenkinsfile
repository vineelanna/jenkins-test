pipeline {
  agent { docker { image 'maven:3.8.4-openjdk-11-slim' } }
  stage {
    stage('build') {
      steps {
        sh 'mvn --version'
      }
    }
  }
}
