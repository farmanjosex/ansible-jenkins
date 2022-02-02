node{
 
    stage('Clone') {
        git 'https://github.com/ludovic-tech/ansible-jenkins.git'
    }
    stage('Ansible') {

    sh 'ansible-playbook -i hosts.yml playbook.yml'
    }
}
