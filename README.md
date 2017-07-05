# Asuka

Conjunto de roles simples para configuração inicial de minha workstation


## Uso

Primeiro baixe as roles pelo galaxy:
`ansible-galaxy install -r requirements.yml --roles-path roles`

Em seguida execute o playbook

`ansible-playbook virtual.yml -i hosts --ask-become-pass`
