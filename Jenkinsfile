pipeline {
    agent any (1)
    stages {
        stage('Build') { (2)
            steps {
                echo "build"
            }
        }
        stage('Test') { (4)
            steps {
              echo "test"
            }
        }
        stage('Deploy') { (6)
            steps {
                echo "deploy"
            }
        }
    }
}
