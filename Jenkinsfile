node {
        stage('clone') {
                git "https://github.com/DouaeChmihi/jenkins-helloworld.git"
        }
        stage('Build') {
                sh label:'', script: 'javac Main.java'
        }
        stage('run') {
                sh label:'', script: 'java Main'
        }
    }

