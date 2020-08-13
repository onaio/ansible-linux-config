Linux Config
============

Use this role to install, configure, and manage generic linux system configuration.

Options
-------

`linux_config_swap_off`, binary, default `True`, turn swap on or off.

> You probably do not want to enable the below, but instead configure this for specific partitions, TODO generalize this so the user can specify the partitions it applies to

`linux_config_noatime_srcs`, list, default empty list, disable access time on the set of src mount points to improve IO.

License
-------

Apache 2

Authors
-------

[Ona Engineering](https://ona.io)
