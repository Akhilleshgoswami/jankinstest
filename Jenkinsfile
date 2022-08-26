pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
               echo 'clone repo'
               sh 'git clone git@github.com:Akhilleshgoswami/jankinstest.git'
               sh 'rm -rf ex.py'
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
