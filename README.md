# Effective Debugging in a Distributed System

Debugging and diagnosing problems in a distributed system is challenging. One
of the best ways remains effective logging. But how exactly do you implement
and maintain effective logging practices in your software applications and
systems?

Almost all software languages have logging libraries available. These
typically do little more than provide the ability to format strings and set a
severity level of message. Severity levels, usually from Debug to Critical,
allow the logging system to filter out messages that are not needed normally,
but allows them to remain in the code, ready to enabled at a moment's notice.

Most Operating Systems also have their own logging facilities, such as the
Windows Event Log and syslog, but these alone only provide destinations for
messages and must still be used properly to be effective debugging and 
diagnostic tools.

See the full manifesto on Effective Debugging in a Distributed System at our
[Wiki](../../wiki).

