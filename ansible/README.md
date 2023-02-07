ansible-playbook -i inventory playbook.yaml 


ansible-playbook -i inventory playbook.yaml --skip-tags="cert"


ansible-playbook -i inventory playbook.yaml --tags="cert"