# tcpsecrets
Linux kernel module to provide access to tcp cookie secrets via /proc/tcp_secrets

## Tested kernels
- 4.2.0-35-generic #40~14.04.1-Ubuntu 
- 4.4.0-34-generic #53~14.04.1-Ubuntu 
- 4.6.0-0.bpo.1-amd64 #1 SMP Debian 4.6.4-1~bpo8+1
- 3.16.0-4-amd64 #1 SMP Debian 3.16.36-1+deb8u1


## Custom kernels
These options are required for module to work:

```
CONFIG_LIVEPATCH=y
CONFIG_FTRACE=y
CONFIG_DYNAMIC_FTRACE=y
CONFIG_DYNAMIC_FTRACE_WITH_REGS=y
CONFIG_FTRACE_MCOUNT_RECORD=y
```
