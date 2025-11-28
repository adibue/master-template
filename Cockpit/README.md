# Cockpit-specific configs

Configs related to [Cockpit](https://cockpit-project.org/).

## Ubuntu

Place or create the Netplan file under `/etc/netplan/10-cockpit.yaml` and apply with `sudo netplan apply` to make networking work in Cockpit.
Make sure to set file permissions to 600.
