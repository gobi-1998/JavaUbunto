pipeline{
    agent any
    stage {
      stage('Checkout') {
        steps {
          checkout scm
        }
    }
    stage('Buld') {
        steps {
            sh 'mvn clean install'
        }
    }
    }
}
