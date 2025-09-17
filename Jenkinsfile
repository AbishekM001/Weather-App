pipeline {
  agent any
  stages {
    stage('SCM') {
      steps {
        git branch: 'main', url: 'https://github.com/AbishekM001/Weather-App.git'
      }
    }
    stage('Done') {
      steps {
        echo "Pipeline steps completed"
      }
    }
  }
}
