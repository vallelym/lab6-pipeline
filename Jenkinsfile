pipeline {
    agent any
    stages {
        stage("Hello") {
            steps {
                sh "echo Hello World"
            }
        }
    }
}' > Jenkinsfile
git add Jenkinsfile
git commit -m "Fix Jenkinsfile syntax"
git push
