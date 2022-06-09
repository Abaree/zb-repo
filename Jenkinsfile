pipeline{
	agent any 
	stages{
		stage('1-git clone'){
			steps{
				git checkout
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