pipeline {
    agent {
        docker {
            image 'node'
        }
    }
    
    stages {
        stage('Build') {
            steps {
            echo 'building or resolving dependencies'
            }
        }
    
        stage ('Test') {
            steps {
                 echo 'running regression tests'
                 sh 'npx cypress run'
            }
        }
    }
    
}
