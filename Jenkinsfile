pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        sh 'ansible-playbook --inventory inventory.yml --extra-vars "repo__user=user" --extra-vars "repo__user_password=P@ssw0rd" --extra-vars "repo__user_become_password=P@ssw0rd" site.yml'
      }
    }

  }
}
