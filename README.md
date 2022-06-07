# wsl2-linux-kernel
Provides pre-built releases of Microsoft's WSL2-Linux-Kernel in a more frequent way than Microsoft does.

* Uses the the [kernel.org](https://kernel.org/) sources
* ... as well as [Microsoft's WSL2 kernel config](https://github.com/microsoft/WSL2-Linux-Kernel/blob/linux-msft-wsl-5.10.y/Microsoft/config-wsl) (the x86 / x86_64 version - no ARM builds supported at the moment)
* ... and an Ubuntu 20.04 (non-WSL) build host
* ... to compile a linux kernel suitable to be used as an up-to-date WSL2 kernel

Find the pre-built binaries in the release section. There's no trojans, malicious stuff or something like that compiled into it. Trust me! :wink: (or compile yourself)

Follow [Microsoft's instructions](https://docs.microsoft.com/en-us/windows/wsl/wsl-config#configure-global-options-with-wslconfig) for how to actually use a custom kernel in your WSL2 installation.
