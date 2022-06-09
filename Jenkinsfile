pipeline{
	agent any 
	stages{
		stage('1-git clone'){
			steps{
				checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[]]])
				stage('1-memory check'){
					steps{
						steps{
							sh 'free -m'
						}
					}
				}
			}
		}

	}
}
