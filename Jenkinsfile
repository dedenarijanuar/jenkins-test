pepline {
  agent any
  stages {
      stage('build'){
          sh 'docker image build -t belanjaquit/testing:1.0.1'
      }
      stage('login'){
          sh 'docker login -u=belanjaquit -pBelanjaQu4j4'
      }
      stage('push'){
          sh 'docker push belanjaquit/testing:1.0.1'
      }
  }
}
