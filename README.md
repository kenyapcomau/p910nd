# p910nd

p910nd is a small printer daemon intended for diskless platforms that does not spool to disk but passes the job directly to the printer. Normally a lpr daemon on a spooling host connects to it with a TCP connection on port 910n (where n=0, 1, or 2 for lp0, 1 and 2 respectively). p910nd is particularly useful for diskless platforms. Common Unix Printing System (CUPS) supports this protocol, it's called the AppSocket protocol and has the scheme socket://. LPRng also supports this protocol and the syntax is lp=remotehost%9100 in /etc/printcap.

The repository at https://sourceforge.net/projects/p910nd/ is being phased out. Packagers please use this and not Sourceforge as the upstream repository now.

## Version

0.97

Note that this is the same version as the last released version from 2014. No features have been added, nor any bugs fixed from that version. Several distributions have packaged this software ready to use. If you are not a developer there is no advantage to cloning this repository. The move to Github is to facilitate any submission of bug fixes and contributions.

## Authors

**Ken Yap** and others

## License

See the [LICENSE](LICENSE.md) file for license rights and limitations (GPL2).
