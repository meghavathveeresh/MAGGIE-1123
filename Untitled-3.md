23/06/25 ansible roles

---
- hosts: webservers
  become: yes
  tasks:
  roles:
  - robertdebock.java
  - robertdebock.tomcat         