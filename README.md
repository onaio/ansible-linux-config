Linux Config
============

Use this role to install, configure, and manage generic linux system configuration.

Options
-------

`linux_config_swap_off`, binary, default `True`, turn swap on or off.

> You probably do not want to enable the below, but instead configure this for specific partitions, TODO generalize this so the user can specify the partitions it applies to

`linux_config_noatime`, binary, default `False`, disable access time on root to improve IO.

License
-------

Apache 2

Authors
-------

[Ona Engineering](https://ona.io)
