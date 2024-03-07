pipeline {
    agent any
    stages {
        stage('git repo & clean') {
            steps {
             
                bat "git pull https://github.com/gopikaaws/jenkinsci.git"
            }
        }
         stage('build') {
            steps {
                 echo("Hello World")
            }
        }
       
    }
}
