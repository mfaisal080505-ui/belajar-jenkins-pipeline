pipeline {
    agent {
        node {
            label "Linux && java21"
        } 
    }
    stages {
        stage('Welcome') {
            steps {
                echo 'Hallo gesss! Log ini sekarang sudah berhasil dan berjalan dengan mulus.'
            }
        }
        stage('Check System') {
            steps {
                echo 'Mengecek waktu server...'
                sh 'date'
            }
        }
    }
}
