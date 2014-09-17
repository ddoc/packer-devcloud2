packer-devcloud2
================

Packer settings to build devcloud2 for Cloudstack testing

Box file is 632M. I followed all the documentation for creating this except I swapped eth0<->eth1 so eth0 could be NAT as vagrant seems to expect, leaving eth1 as host-only. Also im not sure that vagrant is setting promiscuous for eth1 to allow-all.

original documentation [https://cwiki.apache.org/confluence/display/CLOUDSTACK/DevCloud]

recreated using these docs: http://bhaisaab.org/logs/devcloud/

created using packer [https://github.com/ddoc/packer-devcloud2/]
