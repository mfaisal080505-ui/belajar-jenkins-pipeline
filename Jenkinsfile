pipeline {
  agent {
    node {
        label "Linux && java21"
    stages {
        stage('Welcome') {
            steps {
                echo 'Hallo gesss! Log ini sekarang wkwkwk.'
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
