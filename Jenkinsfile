pipeline {
    agent { label 'Jenkins-Agent' }

    tools { 
      jdk 'Java17'
      maven 'Maven3'
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
