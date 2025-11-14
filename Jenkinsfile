pipeline {
    agent any
    stages {
        stage ("Test") {
            steps {
                sh 'git submodule update --init --recursive'
                sh 'bash sub-mod/script.sh'
            }
        }
    }
}
