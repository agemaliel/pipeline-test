pipeline {
    agent {
        node{
            label "production"
        }
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}

post{
    always{
        echo "Hi Alfon, your task is running"
    }
    success {
        echo "Sukses bro:"
    }
    failure {
        echo "gagal nih, coba lagi"
    }
    cleanup {
        echo "cleaning up"
    }
}
