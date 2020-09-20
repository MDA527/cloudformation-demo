pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name ec2-jen --template-body file://ec2.json --region 'us-east-1'" /
                --parameters  ParameterKey=typeofInstance,ParameterValue= $typeofInstance
              }
             }
            }
            }
