## About

This repository contains a collection of FreeBSD patches I have
collected over time and in different situations. I am not the
author of any of these patches but either use them or was involved
in testing them.


## Patch

* [nvidia.patch](nvidia.patch)

Author: corvink

This patch comes from [Beckhoff/freebsd-src](https://github.com/Beckhoff/freebsd-src/commits/phab/corvink/15.0/nvidia-wip/)
and it improves bhyve passthrough support for NVIDIA GPUs. It should be applied
against 15-CURRENT. I don't know if it will be merged upstream but at the time of
writing it has not been.


* [konstanin1.patch](konstanin1.patch), <br>
  [konstanin2.patch](konstanin2.patch)

Author: Konstanin Belousov

These two patches have since been merged into FreeBSD and come from a 
[bug report](https://bugs.freebsd.org/bugzilla/show_bug.cgi?id=285976) 
I filed some time ago.
