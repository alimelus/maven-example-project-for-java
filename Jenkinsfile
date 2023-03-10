pipeline {
   agent {
    node {
        label 'java_node'
    }
   }
     tools { 
        maven 'MAVEN' 
        }
    stages{
      stage("clone code")  {
            steps {
                script {
                    git 'https://github.com/alimelus/maven-example-project-for-java.git';
            }
            }
            }
        stage("mvn build") {
            steps {
                    sh 'mvn clean package'
         
                }
                }
            }
            }
