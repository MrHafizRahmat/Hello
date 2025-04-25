pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Hello App...'
            }
        }
        stage('Simulate Build Step') {
            steps {
                echo 'Simulating build step...'
            }
        }
        stage('Run Tests') {
            steps {
                echo 'Running Tests...'
                echo 'Running basic test...'
            }
        }
        stage('Advanced Test') {
            steps {
                script {
                    echo 'Running advanced test...'
                    def testPassed = false // Simulate test failure

                    if (!testPassed) {
                        error('Advanced test failed!')
                    }
                }
            }
        }
    }
}
