pipeline{
    agent any
    tools {
        maven 'maven3.9'
    }
    stages{
        stage("Cloning Repository"){
            steps{
                echo "Cloning repository"
                echo "Cloning repository completed"
            }
        }
        stage("Building"){
            steps{
                echo "Building package"
                echo "Building package completed"
            }
        }
        stage("Testing"){
            steps{
                echo "Testing package Source"
                echo "Testing package Source completed"
            }
        }
        stage("Artifactory"){
            steps{
                echo "Pushing to artifact"
                echo "Pushing to artifact completed"
            }
        }
        stage("Deploy to web"){
            steps{
                echo "Deploy to Tomcat"
                echo "Deploy to Tomcat completed"
            }
        }

    }
}
