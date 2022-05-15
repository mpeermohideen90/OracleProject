pipeline {
    agent any 
    stages {
        stage('Build') { 
	ws("F:\workspace\") {
	  echo "awesome commands here instead of echo"
		}
            steps {
                echo 'Build done'
            }
        }
        stage('Test') { 
            steps {
                echo 'Test done'
            }
        }
        stage('Deploy') { 
            steps {
                echo 'Deploy done'
            }
        }
    }
}