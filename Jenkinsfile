// timeout code
pipeline {
    agent {
        label 'java-slave'
    }
    stages {
        stage ('Build'){
            step {
                echo "*********Sleeping for 60 seconds*********"
                sleep 60
            }
        }
    }
}
