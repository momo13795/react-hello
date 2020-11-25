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
                    echo "Multiline shell steps works too"
                    ls -lah
		    npm -v
                '''
            }
        }
    }
}
