Mumble Server
-------------------------------------------

Basic installation of Mumble. Installs using PPA(1) and managed using Systemd.

        [mumble]
        localhost

Install mumble on configured server:

        ansible-playbook -i hosts site.yml

---

(1) https://launchpad.net/~mumble/+archive/ubuntu/release