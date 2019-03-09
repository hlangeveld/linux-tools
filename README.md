linux-tools
===========

very basic linux tools


`service-status` produces a summary of the current status of all services configured for the current runlevel.

Less relevant now that `systemd` has been catching on.

Options: -[12345] -- specify runlevel

  -v  -- Dump `init.d <service> status` output


Bugs:

There's little consistency between `init.d` scripts in their reporting.

Output is massaged for decent readability and consistent output.

Once tested on Centos63.
