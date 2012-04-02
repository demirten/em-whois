# EM-Whois

This is a container for the synchronous WHOIS gem which replaces socket communications
with the EventMachine equivalent.  The result is a gem permitting asynchronous WHOIS
lookups.

## TODO

* More elegant approach to reading from the EM::Synchrony::TcpSocket in Whois::Server::Adapters::Base#ask_the_socket
* Specs

## License & Notes

The MIT License - Copyright (c) 2012 [Mike Jarema](http://mikejarema.com)
