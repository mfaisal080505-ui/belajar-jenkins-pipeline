pipeline {
    agent any
    stages {
        stage("Hello") {
            steps {
                echo 'Halo Faisal! Log ini sekarang harusnya panjang.'
            }
        }
    }

    post {
        always {
            echo "I will always say Hello again!"
        }
        success {
            echo "Yay, success"
        }
        failure {
            echo "Oh no, failure"
        }
        cleanup {
            echo "Don't care success or error"
        }
    }
}