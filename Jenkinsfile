pipeline {
	agent any
	stages {
		stage('Clone Repo') {
			steps {
			sh "export AWS_DEFAULT_REGION=us-west-2"
			sh "aws cloudformation create-stack --stack-name myteststack --template-body file://S3Bucket.json --region 'us-west-2'"
			
			}
		}	
	}	
}	