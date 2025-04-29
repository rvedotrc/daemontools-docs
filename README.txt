What and Why
============

This is a collection of supplementary documentation about daemontools
<http://cr.yp.to/daemontools.html>.

To quote the above page,

  daemontools is a collection of tools for managing UNIX services.

  supervise monitors a service. It starts the service and restarts the service
  if it dies. Setting up a new service is easy: all supervise needs is a
  directory with a run script that runs the service.

  multilog saves error messages to one or more logs. It optionally timestamps
  each line and, for each log, includes or excludes lines matching specified
  patterns. It automatically rotates logs to limit the amount of disk space used.
  If the disk fills up, it pauses and tries again, without losing any data.

It's not a reference manual for the daemontools programs.  Please refer to
your system's man pages (if provided), or the daemontools home page (see
above, otherwise), for that.

Rather, it's a collection of documentation about how to use daemontools in
practice.

Although the daemontools home page includes documentation which accurately and
succinctly describes what each program in the suite does, many people find
that it's hard then to work out how to make best use of those programs in the
real world.  Until you understand how daemontools works, it's easy to get
yourself tangled up in knots.

This documentation exists to help you make the best use of daemontools,
avoiding the common traps and pitfalls.

All of the examples provided are on Gnu/Linux.  You may have to vary some of
the commands (lsof, pkill, etc) on other systems.

Contents
========

README.txt              This file
introduction.txt        An introduction to daemontools
debugging.txt           How to debug service problems and disentangle things

Credits
=======

The documentation lives on github <https://github.com/rvedotrc/daemontools-docs>
and is maintained by Rachel Evans <https://rachelevans.org/>.
