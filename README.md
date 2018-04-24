# Asuka

Conjunto de roles simples para configuração inicial de minha workstation


## Compatibilidade

As roles foram testadas na versão desktop do Xubuntu **16.04.2 LTS (x64)**

Contudo algumas tasks são pessoais de acordo com meu dia-a-dia.


## Uso

Primeiro baixe as roles pelo galaxy:

`ansible-galaxy install -r requirements.yml --roles-path roles`

Em seguida execute o playbook

`ansible-playbook playbook.yml -i inventory.ini --ask-become-pass`

> A opção `--ask-become-pass` para definir a senha usada para torna-se root
>
> Lembre-se de conferir se o hosts está correto de acordo com suas necessidades


## Roles Externas

 * [geerlingguy.docker](https://github.com/geerlingguy/ansible-role-docker)
