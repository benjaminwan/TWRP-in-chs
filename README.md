使用了suky的汉化代码，感谢suky。

但目前只汉化了720x1280分辨率的界面，因其它分辨率暂时用不到。

suky的说明请参考[suky/TWRP_cn](https://github.com/suky/TWRP_cn "suky")

这个是官方的[编译说明](http://forum.xda-developers.com/showthread.php?t=1943625 "Guide")

A850[编译教程](http://blog.csdn.net/benjaminwan/article/details/8952736 "benjaminwan")

A840[编译教程](http://blog.csdn.net/benjaminwan/article/details/9070089 "benjaminwan")

**Team Win Recovery Project (TWRP)**

The goal of this branch is to rebase TWRP onto AOSP while maintaining as much of the original AOSP code as possible. This goal should allow us to apply updates to the AOSP code going forward with little to no extra work.  With this goal in mind, we will carefully consider any changes needed to the AOSP code before allowing them.  In most cases, instead of changing the AOSP code, we'll create our own functions instead.  The only changes that should be made to AOSP code should be those affecting startup of the recovery and some of the make files.

If there are changes that need to be merged from AOSP, we will pull the change directly from AOSP instead of creating a new patch in order to prevent merge conflicts with AOSP.

This branch is under final testing and will be used shortly for public builds, but has not officially been released.

You can find a compiling guide [here](http://forum.xda-developers.com/showthread.php?t=1943625 "Guide").

[More information about the project.](http://www.teamw.in/project/twrp2 "More Information")

If you have code changes to submit those should be pushed to our gerrit instance.  A guide can be found [here](http://teamw.in/twrp2-gerrit "Gerrit Guide").
