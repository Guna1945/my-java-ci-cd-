pipeline {
    agent any
    stages {
        stage('1. Build (CI)') {
            steps {
                echo 'Condition 1 satisfied: Running simulated compilation...'
                bat 'echo Application compiled successfully' 
            }
        }
        stage('2. Test (CI)') {
            steps {
                echo 'Condition 2 satisfied: Running simulated tests...'
                bat 'echo Tests passed with zero failures'
            }
        }
        stage('3. Deploy (CD)') {
            steps {
                echo 'Condition 3 satisfied: Deploying to target environment...'
                bat 'echo Deployment simulated and artifact is live'
            }
        }
    }
}
