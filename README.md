linux-tools
===========

very basic linux tools


`service-status` produces a summary of the current status of all services configured for the current runlevel.

Options: -[12345] -- specify runlevel
  -v  -- Dump `init.d <service> status` output


It's not SMF, and the different init.d scripts aren't very consistent in their reporting.
Output is massaged for decent readability and consistent output.

Tested on Centos63.
