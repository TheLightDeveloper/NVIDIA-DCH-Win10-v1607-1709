# NVIDIA-DCH-Win10-v1607-1709

Since September 2021, NVIDIA has stopped releasing old WHQL releases that was used primarily on older versions of Windows prior to Windows 10, version 1803. It is possible to patch to force DCH drivers to install on older Windows 10 releases since early support was added sometime during the development of Windows 10 Anniversary Update. This was done by modifying the *.inf files to allow the installer to run on a unsupported build. The last known version that works with this workaround is 537.58, released on October 10th, 2023.

Tested on NVIDIA Geforce 970 running on Windows 10 Enterprise LTSB 2016. I cannot guarantee that newer Geforce GPUs may work with this patch as I don't have the appropriate hardware to test it on.  
