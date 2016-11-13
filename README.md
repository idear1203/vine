# Vine

The original vine repository has not been updated for a long time. Compilation failure caused by incompatibility occurs. After several days searching solution, I finally get successful compilation. My solution mainly depends on a patch I found from [bitblaze user](groups.google.com/group/bitblaze-users) mailing list. I have put [the patch](https://github.com/idear1203/vine/blob/master/vine-1.0-1404.patch) in this repository.

This repository aims to make it easier for vine users to build vine.

First, you should follow [installation instructions](http://bitblaze.cs.berkeley.edu/release/vine-1.0/howto.pdf) to satisfy prerequisites.

Then, build step is just as simple as configure and make:

1. cd `path/to/vine`(the dictionary vine locates in).
2. run `./configure`
3. run `make`

You compilation should be done in this way. If you meet any trouble, please feel free to connect me.

For more information about Vine and other BitBlaze software, see offical [README](https://github.com/idear1203/vine/blob/master/README).
