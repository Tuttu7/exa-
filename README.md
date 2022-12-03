 #### Exa is a modern-day replacement for the Linux ls command
 
 
 ```
 [root@ip-172-31-87-84 ~]# dnf install cargo

[root@ip-172-31-87-84 ~]# cargo install exa

Installing /root/.cargo/bin/exa
   Installed package `exa v0.10.1` (executable `exa`)
warning: be sure to add `/root/.cargo/bin` to your PATH to be able to run the installed binaries


[root@ip-172-31-87-84 ~]# echo "$PATH"
/root/.local/bin:/root/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin

[root@ip-172-31-87-84 bin]# export PATH=$PATH:/root/.cargo/bin/
[root@ip-172-31-87-84 bin]# echo "$PATH"
/root/.local/bin:/root/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/root/.cargo/bin/

```
 #### Tree view. The level determines the depth of the listing; this is set to two. If you want to list more subdirectories and files, increase the level's value.

![exa1](https://github.com/Tuttu7/exa-/blob/main/Screenshot%20from%202022-12-03%2012-30-27.png)


 #### To list directories and subdirectories recursively, you can --recurse or -R option. It creates a separate listing for each sub-directory

![exa2](https://github.com/Tuttu7/exa-/blob/main/Screenshot%20from%202022-12-03%2012-31-47.png)

```
exa -T
```

![exa2](https://github.com/Tuttu7/exa-/blob/main/Screenshot%20from%202022-12-03%2012-32-20.png)


#### Exploring xattrs (extended file attributes) in exa, --extended 

![exa3](https://github.com/Tuttu7/exa-/blob/main/Screenshot%20from%202022-12-03%2012-44-36.png)

