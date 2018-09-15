pipeline{
        agent any
          stages{
           stage('build'){
            steps {
            sh 'chmod u+x first.yml'
            sh 'ansible-playbook first.yml'
          }
      }
     }
 }
