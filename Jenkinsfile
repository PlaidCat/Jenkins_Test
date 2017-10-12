pipeline {
    agent any 
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello World!"'
		sh '''
		    echo "multiline shell steps works too"
		    ls -lah
		'''
            }
        }
    }
}
