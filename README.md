#Here we will use low-level networking information such as IP and ICMP headers. Network sniffers have a pratical use before and after exploitation. This will help you better understand Python, networking and upgrade your network coding skills. 

- sniffer.py

The sniffer's main goal is to discoveer hosts on a target network. Is this script we use input/output control (IOCTL) which enables promiscuous modeon the network interface and is also a means for user space programs to communicate with the kernel mode components. 

- sniffer_ip_header_decoder.py

Here we decode the entire IP header and extract the protocol type, source and destination IP address.
