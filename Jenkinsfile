pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Hello App...'
                // Optional: npm install
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
    }
}
