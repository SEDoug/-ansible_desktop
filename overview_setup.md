 1900  sudo apt install ansible<br>
 1901  ansible all --key-file ~/.ssh/ansible -i inventory -m ping<br>
 1902  ansible-inventory --version<br>
 1915  ansible all --key-file ~/.ssh/ansible -i inventory -m ping<br>
 1918  vi ansible.cfg<br>
 1920  ls /etc/ansible/<br>
 1921  cat /etc/ansible/<br>
 1922  cat /etc/ansible/ansible.cfg<br>
 1924  ansible all -m ping<br>
 1925  ansible all --list-hosts<br>
 1926  ansible all -m gather_facts<br>
 1932  git commit -m "first commit version of ansible.cfg file"<br>
 1946  cd ansible_desktop/<br>
 1947  ansible all -m gather_facts<br>
 1986  cd ansible_desktop/<br>
 1987  history | grep ansible<br>
 1988  ansible all -m ping<br>
 2018  cd ansible_desktop/<br>
 2021  cat ../.ssh/ansible.pub<br>
