pipeline{

agent any

stages{
	stage('SCM'){
		steps {
			echo "pulling code from SCM"
			echo "inside the 2nd step of SCM stage"
		}
	}
	stage('Deploy'){
		steps {
			echo "Deploying code in webserver"
		}
	}
	stage('Test'){
		steps {
			echo "Testing the code in webserver"
		}
	}
}
}