pipeline{
	agent any 
	stages{
		stage('1-git clone'){
			steps{
				checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/Abaree/zb-repo.git']]])
				
			}
		}

	}
}
