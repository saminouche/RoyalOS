# RoyalOS

## intro
RoyalOS is an os that I'm making to teach myself and others, that's why I made it public under the CC.0 lisence (public domain).
I commented everything and I will continue to do so in order for everybody to be able to read, give feedback and share about this os.

BTW the name comes from my twitch pseudo RoyalDuckmc, channel on which I livestream the advancement on the OS between others subjects.

## build
For now the scripts are only aviable for debian based linux distros (should work on others linux distros with a bit of digging).
To build on windows, I recomend using either WSL or a virtual machine as you want to be under linux to be able to develop an OS.
For mac users I think it shouldn't be so hard given that you can compile grub commandline tools from source, even if the best practice is still to use a linux machine.

1.
> run `git clone https://github.com/saminouche/RoyalOS`
2.
> run `./init.sh`
3.
> run `./make`

you should be all done, if you're missing a package don't hesitate to open an issue or a pull request to midify init.sh

## run
Some debugging tools such as E9 port only work with qemu so I advice you to run `./run`
