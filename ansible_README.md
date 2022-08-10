# aba_automation
# CONFIG: playbooks, roles, inventory, and variables files in git
# MODULES FOR LINUX: 

#copy
- name: Ensure MOTD file is in place
  copy:
    src: files/motd
    dest: /etc/motd
    owner: root
    group: root
    mode: 0644

# synchronize

# template, user, package, service, firewall, file, lineinfile, unarchive, command

