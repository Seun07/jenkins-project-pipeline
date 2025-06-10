pipeline {
    agent any
    stages{
        stage("GitHub checkout....") {
            steps {
                script {
 
                    git branch: 'main', url: 'https://github.com/Seun07/jenkins-project-pipeline.git' 
                }
            }
        }
         stage('building image'){
            steps {

                script {
                    sh 'echo "print out eneviromenst"'  
                    sh 'printenv'
                    sh 'git version'
                    sh 'docker build -t seun0706/sheck-app:1.0 .'
                }
            }
        }


    }
   
   
    }