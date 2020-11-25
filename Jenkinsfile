pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
		sh 'export PATH=/usr/local/bin:$PATH'
                sh 'echo "Hello World"'
		sh '$PATH'
                sh '''
		    whoami
		    pwd
                  '''
            }
        }
    }
}
