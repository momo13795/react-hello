pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
		sh 'export PATH=/usr/local/bin:$PATH'
                sh 'echo "Hello World"'
		sh '$PATH'
                sh '''
                    export PATH=/usr/local/bin:$PATH
		    whoami
		    pwd
                    echo "Multiline shell steps works too"
                    ls -lah
                    source /etc/profile
		    npm -v
                '''
            }
        }
    }
}
