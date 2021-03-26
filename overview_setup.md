 1900  sudo apt install ansible
 1901  ansible all --key-file ~/.ssh/ansible -i inventory -m ping
 1902  ansible-inventory --version
 1915  ansible all --key-file ~/.ssh/ansible -i inventory -m ping
 1918  vi ansible.cfg
 1920  ls /etc/ansible/
 1921  cat /etc/ansible/
 1922  cat /etc/ansible/ansible.cfg
 1924  ansible all -m ping
 1925  ansible all --list-hosts
 1926  ansible all -m gather_facts
 1932  git commit -m "first commit version of ansible.cfg file"
 1946  cd ansible_desktop/
 1947  ansible all -m gather_facts
 1986  cd ansible_desktop/
 1987  history | grep ansible
 1988  ansible all -m ping
 2018  cd ansible_desktop/
 2021  cat ../.ssh/ansible.pub
