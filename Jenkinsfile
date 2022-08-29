pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
               echo 'clone repo'
                sh 'python ex.py' 
               
                sh 'git clone https://github.com/Akhilleshgoswami/jankinstest'
            
            }}
             stage('build') {
            steps {
                echo 'Hello World'
            }}
             stage('test') {
            steps {
                echo 'Hello World'
            }}
             stage('deploy') {
            steps {
                echo 'Hello World'
            }}
    }
}
