
# THIS REPOSITORY HAS MOVED

New URL: https://git.goyman.com/kuon/ansible-freebsd-logstash

Why I moved everything out of GitHub:

https://github.com/kuon/WhyILeftGithub/blob/main/README.md

----


# THIS REPOSITORY HAS MOVED

New URL: https://git.goyman.com/kuon/ansible-freebsd-logstash

Why I moved everything out of GitHub:

https://github.com/kuon/WhyILeftGithub/blob/main/README.md

----


# THIS REPOSITORY HAS MOVED

New URL: https://git.goyman.com/kuon/ansible-freebsd-logstash

Why I moved everything out of GitHub:

https://github.com/kuon/WhyILeftGithub/blob/main/README.md

----

FreeBSD-logstash
================

Install logstash and elasticsearch.


**DISCLAIMER**: This role has been created for my personal use and come with
no warranty. This role is very opiniated and may cause trouble with your install.



Requirements
------------

FreeBSD, runit

Role Variables
--------------


- `logstash_cluster_name`, the name of the elasticsearch cluster
- `logstash_directory`, install directory of logstash, default to `/srv/logstash` 
- `logstash_node_name`, the name of the elasticsearch node, default to `{{ inventory_hostname }}`
- `logstash_port`, the syslog TCP port of the logstash listener, default to 51400


License
-------

MIT

Author Information
------------------

Ansible role by Nicolas Goy @kuon.

