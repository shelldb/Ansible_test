pipeline{
        agent any
          stage{
           stage('build'){
            steps {
            sh 'chmod u+x first.yml'
            sh 'ansible-playbook first.yml'
          }
      }
     }
 }
