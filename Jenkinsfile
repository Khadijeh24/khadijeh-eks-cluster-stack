pipeline {
agent any 
  stages {
    stage('Build Repo') {
      steps {
        sh "aws cloudformation create-stack --stack-name KhadijehEKSStack1 --template-body file://khadijeh-eks-cluster.yaml --region 'us-east-1'"
      }
    }
  }

}
