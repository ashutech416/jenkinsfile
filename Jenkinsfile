pipeline {
    agent any 
    stages {
        stage('job2') { 
            steps {
              build "job2"
            }
        }
        stage('pipeline-job') { 
            steps {
                build "pipeline-job"
            }
        }
    }
}
