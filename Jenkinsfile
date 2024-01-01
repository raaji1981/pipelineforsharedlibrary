@Library(['my-shared-library.git@main']) _

pipeline {
    agent any

    stages {
        stage('Example Stage') {
            steps {
                // Use the shared step from the library
                mySharedStep()

            }
        }
    }
}
