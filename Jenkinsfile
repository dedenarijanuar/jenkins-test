pipeline {
  agent any
  stages {
      stage('build'){
        steps{
          sh 'docker image build -t belanjaquit/testing:1.0.1 .'
        }
      }
      stage('login'){
        steps{
          sh 'docker login -u=belanjaquit -pBelanjaQu4j4'
        }
      }
      stage('push'){
        steps{
          sh 'docker push belanjaquit/testing:1.0.1'
        }
      }
  }
}
