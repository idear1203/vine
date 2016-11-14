# Vine

The original vine repository has not been updated for a long time. Compilation failure caused by incompatibility occurs. After several days searching solution, I finally get successful compilation. My solution mainly depends on a patch I found from [bitblaze user](groups.google.com/group/bitblaze-users) mailing list. I have put [the patch](https://github.com/idear1203/vine/blob/master/vine-1.0-1404.patch) in this repository.

This repository aims to make it easier for vine users to build vine.

My host OS version is Ubuntu 16.04 Linux 32 bit.

```
$ lsb_release -a
No LSB modules are available.
Distributor ID: Ubuntu
Description:    Ubuntu 16.04.1 LTS
Release:    16.04
Codename:   xenial
$ uname -a
Linux aaron-pc 4.4.0-31-generic #50-Ubuntu SMP Wed Jul 13 00:06:14 UTC 2016 i686 i686 i686 GNU/Linux
```

**To solve an incompatibility error due to newer version of the `ocamlgraph` library, I choose to compile `ocamlgraph` library from source. The version I used is 1.8.2(Note `ocamlgraph` in Ubuntu package manager is too new for vine, leading to some error). You can obtain the source for the latest version of `ocamlgraph` from <http://ocamlgraph.lri.fr/>**

First, you should follow [installation instructions](http://bitblaze.cs.berkeley.edu/release/vine-1.0/howto.pdf) to satisfy prerequisites.

Then, build step is just as simple as configure and make:

1. cd `path/to/vine`(the dictionary vine locates in).
2. run `./configure`
3. run `make`

You compilation should be done in this way. If you meet any trouble, please feel free to connect me.

For more information about Vine and other BitBlaze software, see offical [README](https://github.com/idear1203/vine/blob/master/README).
