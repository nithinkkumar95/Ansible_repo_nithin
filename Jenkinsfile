pipeline {
    agent any
    stages {
        stage(Install_tomcat) {
           steps {
               sh 'sudo ansible-playbook /etc/ansible/install_tomcat.yml'
           } 
        }
    }
}
