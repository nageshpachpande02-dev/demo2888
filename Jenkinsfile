pipeline {
    agent any 
    tools {
        nodejs 'npm'
    }
    environment {
        Name = "Mantasha"
    }

    stages {
        stage('clone') {
            steps {
                echo 'Hello World'
                git branch: 'main', url: ' https://github.com/nageshpachpande02-dev/demo2888.git'
'
            }
        }
         stage('build') {
            steps {
                echo 'Hello World'
                sh 'npm i'
            }
        }
         stage('building the artifact') {
            steps {
                echo 'Hello World'
                sh 'npm run build'
            }
        }
    }
}
