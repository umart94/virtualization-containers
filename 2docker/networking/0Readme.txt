vmware virtual machines ( older versions) do not work on HyperV

Intel VT,VT-d,VT-x (whatever) is different from HyperV

Intel VT is virtualization technology for running multiple DIFFERENT
VMS , using the hardware / software, running multiple seperate operating system guest machines on the host machines.

they are isolated.



HyperV, is a native hypervisor
vmware is a virtual machine monitor / hypervisor, that makes multiple seperate operating systems (virtual machines)

the latest versions of vmware do support hyperv.








HyperV, a native hypervisor when installed on windows will allow Docker to run natively on windows.


OS-level virtualization is an operating system paradigm in which the kernel allows the existence of multiple isolated user space instances. Such instances, called containers (LXC, Solaris containers, Docker), Zones (Solaris containers), virtual private servers (OpenVZ), partitions, virtual environments (VEs), virtual kernels (DragonFly BSD), or jails (FreeBSD jail or chroot jail),[1] may look like real computers from the point of view of programs running in them. A computer program running on an ordinary operating system can see all resources (connected devices, files and folders, network shares, CPU power, quantifiable hardware capabilities) of that computer. However, programs running inside of a container can only see the container's contents and devices assigned to the container.
On Unix-like operating systems, this feature can be seen as an advanced implementation of the standard chroot mechanism, which changes the apparent root folder for the current running process and its children. In addition to isolation mechanisms, the kernel often provides resource-management features to limit the impact of one container's activities on other containers.
The term container, while most popularly referring to OS-level virtualization systems, is sometimes ambiguously used to refer to fuller virtual machine environments operating in varying degrees of concert with the host OS, e.g. Microsoft's Hyper-V containers.
