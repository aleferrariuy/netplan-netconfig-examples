# netplan-netconfig-examples
Files with network configuration examples for use with Canonical "netplan".

Sometimes, for those of us who are just starting out (or not so much), the netplan syntax in its YAML files can confuse us.

The idea, to share experiences.

How to verify the configuration?
 ~~~
sudo netplan try
~~~
How to apply the changes?
 ~~~
sudo netplan apply
~~~
A good recommendation: always back up your functional .yaml configuration file before making changes

You find it in /etc/netplan/ (Ubuntu)
