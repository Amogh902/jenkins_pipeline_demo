// 'pipeline' is the root block of a Declarative Jenkins Pipeline.
// Everything related to our pipeline goes inside this block.
pipeline {

    // 'agent' tells Jenkins WHERE this pipeline should execute. 'any' means:
    // "Run this pipeline on any available Jenkins executor/agent."
    // In our lab, Jenkins itself has executors, so Jenkins will run the pipeline on the Jenkins controller.
    agent any


    // 'stages' is a container for all the major stages of our pipeline.
    // Stages help us organize the CI/CD process into understandable sections such as Build, Test, Deploy.
    stages {


        // 'stage' defines one logical phase of the pipeline.
        // The name inside stage() is displayed in the Jenkins UI.

        stage('Build') {

            // 'steps' contains the actual commands/actions Jenkins should execute during this stage.

            steps {

                // 'echo' simply prints a message in the Jenkins console output.

                echo 'Building Hello World application'
            }
        }


        // Second stage
        stage('Test') {

            // Actions performed during the Test stage.

            steps {

                // Print a message to the Jenkins console.

                echo 'Testing Hello World application'
            }
        }


        // Third stage
        stage('Deploy') {

            // Actions performed during Deploy.

            steps {

                // Print a message to the Jenkins console.
                
                echo 'Deploying Hello World application'
            }
        }
    }
}