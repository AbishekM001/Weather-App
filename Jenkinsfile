pipeline {
  agent any
  stages {
    stage('SCM') {
      steps {
        git branch: 'webhookdemo', url: 'https://github.com/AbishekM001/Weather-App.git'
      }
    }
    stage("Build and Unit Test") {
      steps {
        sh 'mvn clean package' // This will generate the JAR and run tests
      }
    }
    stage('Done') {
      steps {
        echo "Pipeline steps completed"
      }
    }
  }
}
