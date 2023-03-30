pipeline {
    agent any
    stages {
        stage('Stage 1') {
            steps {
                // define the first job in stage 1
                sh 'echo "Hello from Job 1 in Stage 1"'
                
                // define the second job in stage 1
                sh 'echo "World from Job 2 in Stage 1"'
            }
        }
        stage('Stage 2') {
            steps {
                // define the first job in stage 2
                sh 'echo "Greetings from Job 3 in Stage 2"'
                
                // define the second job in stage 2
                sh 'echo "Salutations from Job 4 in Stage 2"'
            }
        }
    }
}
