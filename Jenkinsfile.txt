pipeline {
    agent any

    stages {
      
        stage('build') {
            steps {
                echo 'development is successful'
            }
        }
    stage('test') {
        steps {
            echo 'testing is successful'
        }
    }
    stage('deployment') {
        steps {
            echo 'deployment is successful'
        }
    }
        }
    }

