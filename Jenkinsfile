node{
 
    stage('Clone') {
        git 'https://github.com/farmanjosex/ansible-jenkins.git'
    }
    stage('Ansible') {

    sh 'ansible-playbook -i hosts.yml playbook.yml'
    }
}
