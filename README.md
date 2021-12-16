# Glibc_updated
2.31 glibc libs for arm, arm64 & x86_64


# Install

-For x86_64 (PCs)
```
cd ~
git clone https://github.com/IsaacMvmv/Glibc_updated .glibc
```

-For arm64
```
cd ~
git clone -b arm64 https://github.com/IsaacMvmv/Glibc_updated .glibc
```

-For armhf 
```
cd ~
git clone -b arm https://github.com/IsaacMvmv/Glibc_updated .glibc
```

# Using:
You can use it with this command: ```LD_LIBRARY_PATH=~/.glibc/lib:$LD_LIBRARY_PATH LD_PRELOAD=~/.glibc/lib/libc.so.6 %command%```

But maybe its annoying, and you may need a script which does that, then add in your ~/.bashrc/.zshrc etc...
```alias glc='LD_LIBRARY_PATH=~/.glibc/lib:$LD_LIBRARY_PATH LD_PRELOAD=~/.glibc/lib/libc.so.6'```
After restarting terminal you should do     ```glc %command%```

Enjoy! :D
