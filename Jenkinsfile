pipeline {
   agent any 
   parameters {
       string(name: 'Greeting', defaultValue: 'Hello', description: 'how should i greet the world?')
       }
       stages {
          stage('example') {
            steps {
               echo "${params.greeting} world!"
               }
             }
           }
        }   
