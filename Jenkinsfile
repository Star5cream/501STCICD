pipeline {
    agent any

    stages {
        stage('git checkout'){
            steps{
             git branch: 'main', url: 'https://github.com/Star5cream/501STCICD.git'
            }
        }
        stage('test'){
            steps{
                sh 'echo test jb'
            }
        }
    }

}