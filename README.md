# rawlinux

Barebones Linux distribution based on 6.13.0 kernel.

### Why?

Because Alpine doesn't suit my infrastructure needs. 

Also, I want full control over which drivers are included - I don't need graphics on Kubernetes.

### How to run it

Make sure you have `qemu` installed: `sudo apt install qemu-system-x86`,
launch it with `qemu-system-x86_64 disk.img`

### Roadmap

* enable non-static libraries
* publish a live boot USB
