pipeline{
  agent any


stages{
	stage('Test'){
	steps{
	sh '''
		cd /tmp/
		echo $(date) Hello world >> notes.txt
		cat /tmp/notes.txt'''

	}
	}

}
}

