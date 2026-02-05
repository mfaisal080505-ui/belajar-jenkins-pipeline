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
                echo("Hello Build 1")
                sleep(3)
                echo("Hello Build 2")
                echo("Hello Build 3")
            }
        }

        stage("Test") {
            steps {
                echo 'Halo Faisal! Log ini sekarang berhasil melakukan test.'
                echo("Hello Test 1")
                pwd
                tmp : boolean
                ls -l
            }
        }
    
        stage("Deploy") {
            steps {
                echo 'Halo Faisal! Log ini sekarang berhasil melakukan deploy.'
                echo("Hello Deploy 1")
                sleep(5)
                echo("Hello Deploy 2")
                echo("Hello Deploy 3")
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
