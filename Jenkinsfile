pipeline {
    agent {
        docker {
            image 'centos'
        }
    }
    stages {
        stage('This is a test stage!') {
            steps {
                sh """
                    echo "I am in a container!"
                    cat /etc/hostname
                """
            }
        }
    }
}