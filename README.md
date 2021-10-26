Linux Config
============

Use this role to install, configure, and manage generic linux system configuration.

Options
-------

`linux_config_swap_off`, binary, default `True`, turn swap on or off.

`linux_config_noatime_srcs`, list, default empty list, disable access time on the set of src mount points to improve IO.

`linux_config_tcp_fin_timeout`, integer, default 15, TCP FIN timeout value in seconds default linux appears to default this to 60, we're defaulting it lower.

`linux_config_tcp_tw_reuse`, boolean as integer, default 1, if non zero allow tcp to reuse sockets in the TIME_WAIT state for new connections.

`linx_hard_nofile`, integer, default 65535, maximum number of open file descriptors on the linux system, hard limit.
`linux_soft_nofile`:integer, default 65535, maximum number of open file descriptors on the linux system, soft limit.
`linux_hard_nproc`, integer, default 16384, maximum allowed number of processors per user, hard limit.
`linux_soft_nproc`, integer, default 16384, maximum allowed number of processors per user, soft limit.

License
-------

Apache 2

Authors
-------

[Ona Engineering](https://ona.io)
