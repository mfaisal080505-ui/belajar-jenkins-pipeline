pipeline {
    agent {
        node {
            label "Linux && java21"
        }
    }

    stages {
        stage("Build") {
            steps {
                echo 'Halo Faisal! Log ini sekarang berhasil melakukan build.'
            }
        }

        stage("Test") {
            steps {
                echo 'Halo Faisal! Log ini sekarang berhasil melakukan test.'
            }
        }
    
        stage("Deploy") {
            steps {
                echo 'Halo Faisal! Log ini sekarang berhasil melakukan deploy.'
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
