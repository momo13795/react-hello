pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
		nodejs('node-v14.15.1'){
		}
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
		    npm install 
                '''
            }
        }
    }
}
