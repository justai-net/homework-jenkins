# homework-jenkins
Deploy containerised Jenkins with Ansible, or with docker-compose.

Pull Image
```
# docker pull justai/homework-jenkins
```

Start Jenkins
```
# docker-compose up
```

Use Ansible playbook to install Docker, Pull Image, Start Image
```
# ansible-playbook -i inventory playbooks/deploy-jenkins.yml
```
