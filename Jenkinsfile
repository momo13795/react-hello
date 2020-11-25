pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
		sh 'echo $PATH'
                sh '''
		    whoami
		    pwd
                    echo "Multiline shell steps works too"
                    ls -lah
		    npm install 
                '''
            }
        }
    }
}
