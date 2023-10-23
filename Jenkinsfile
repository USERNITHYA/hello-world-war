pipeline {
    agent none
    stages {
        stage('SCM') {
            steps {
              sh `rm -rf hello-world-war`
              sh `git clone https://github.com/USERNITHYA/hello-world-war.git`
            }
        }
    }
}
