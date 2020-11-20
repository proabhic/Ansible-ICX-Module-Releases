# Ansible-Release Interim module updates

The ansible module in this folder are interim updates which are yet to be approved by Ansible community.
The Interim ansible modules are submitted to community for approval on quarterly basis [JFM/AMJ/JAS/OND].

Documentation for ICX module that are part of official ansible release can be found here:
https://docs.ansible.com/ansible/2.9/modules/list_of_network_modules.html#icx

To use interim release:
1. Download ansible.tar.gz and easy_install
2. Run on terminal:
- chmod +x easy_install
- ./easy_install

Above commands will detect where Ansible is installed, overwrite modified files and add new icx_modules.

# Bug Jiras:Modules

FI-223408, FI-218627: icx_ping.py  
FI-22089: icx_banner.py, icx_config.py, icx_facts.py, icx_l3_interface.py, icx_lldp.py, icx_ping.py, icx_system.py,  icx_vlan.py, icx_command.py, icx_copy.py,icx_interface.py, icx_linkagg.py, icx_logging.py, icx_static_route.py, icx_user.py  
FI-223410, FI-218629, FI-218628: icx_vlan.py
FI-215386: icx_command.py  
FI-216707, FI-220009: icx_facts.py  
FI-216695: icx_system.py  

