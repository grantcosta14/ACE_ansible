# ACE_ansible

installs:
- JDK 8
- apache maven
- git
- apache tomcat
- mongodb
- npm
- nodejs
- rubygems for openshift

to run:
- `yum install ansible` in Terminal
- `git clone` this repository to your desktop
- navigate to cloned ACE_ansible repository
- run `ansible-playbook playbook.yml --ask-sudo-pass` from inside ACE_ansible
  - you will need to enter your local username (i.e. emehlenb)
