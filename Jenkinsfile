node('master') {
  stage('checkout') {
    checkout scm
  }
  stage('gradle') {
    sh 'chmod +x ./gradlew'
    sh './gradlew clean build'
  }
  
}
