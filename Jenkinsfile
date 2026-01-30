pipeline {
    agent any
    stages {
        stage('Hello from VS Code') {
        steps {
            echo 'Hello World, i have written this in VS Code'
        }}
        stage(name: 'Cloning Git repo') {
            steps {
                echo 'Cloning git repo'
                git 'https://github.com/streak2508/new.git'
            }
        }
    }
}
