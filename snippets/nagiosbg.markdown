Background
----------

This resource type is autogenerated
using the model developed in
[Naginator](http://projects.reductivelabs.com/projects/naginator),
and all of the Nagios types are generated using the same code and
the same library.

This type generates Nagios configuration statements in
Nagios-parseable configuration files. By default, the statements
will be added to `/etc/nagios/<type>.cfg`, but you can
send them to a different file by setting their `target` attribute.

WARNING: You can purge Nagios resources using the `resources` type, but
*only* in the default file locations. This is an architectural
limitation.
