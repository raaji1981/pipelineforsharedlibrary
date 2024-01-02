@Library('my-shared-library@dev') _

pipeline {
    agent any

    stages {
        stage('Example Stage') {
            steps {
                // Use the shared step from the library
                mySharedStep()
                firstsharedfile()

            }
        }
    }
}
