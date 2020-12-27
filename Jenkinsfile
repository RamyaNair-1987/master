pipeline {
   stage('Initialize')
    {
        def dockerHome = tool 'docker'
        env.PATH = "//usr/local/bin/:${env.PATH}"
    }
    stages {
        stage('build') {
            steps {
                sh 'docker pull maven:3.3.3'
                sh 'mvn --version'
            }
        }
    }
}
