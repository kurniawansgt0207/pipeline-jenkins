pipeline {
    agent any

    stages {
        stage("Proses 1") {
            steps {
                echo "Selamat Data di Multimatics"
            }
        }

        stage("Proses 2") {
            steps {
                echo "Belajar DevOps"
            }
        }
    }

    post {
        always {
            echo "Proses selesai dilakukan"
        }

        success {
            echo "Seluruh Proses berhasil dijalankan sampai selesai"
        }

        failure {
            echo "Proses Gagal dijalankan sampai dengan selesai"
        }
    }
}