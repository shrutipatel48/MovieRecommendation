pipeline {
    agent any

    options {
        disableConcurrentBuilds()
    }

    triggers {
        cron('* * * * *')
    }

    stages {
        stage('Execute') {
            steps {
                timeout(time: 1, unit: 'HOURS') {
                    echo "Running task every minute"
                }
            }
        }
    }
}
