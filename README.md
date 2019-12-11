# This is Ansible playbook that can help with adding or changing user and config around that process

Some instruction how to:
1) cd ~
2) git clone https://github.com/mixua/epam_ansible.git epam_ansible
3) cd epam_ansible; change the destination host or ip in inventory file.
4) ansible-playbook -i inventory user_add.yml --check -vvv

'#' but the last test could be false(in first time) otherwise it good way to see what for and how is it works.
