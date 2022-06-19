essential tools, missing some custom configs (wireguard, btrbk)
1. configure host(s) in `hosts.ini`, make sure you set up passwordless login via ssh and user is `sudo`able
2. `ansible-galaxy install -r requirements.yaml`
3. `ansible-playbook site.yaml` (with `-K` if needed)

created for simple and fast configuring fedora just after install.

