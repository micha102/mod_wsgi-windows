Python Windows wheels for mod_wsgi on Apache httpd.
Compiled with Github Actions.
The workflow detects the last httpd version released by Apache Lounge and compiles mod_wsgi for the Python version I like (for now it's Python 3.13 and 3.14)
I compile it for the bitness I like, too. Which is x64 (amd64)
GrahamDumpleton/mod_wsgi (thanks!) provides [source code](https://github.com/GrahamDumpleton/mod_wsgi) for building it, so please use it, try your maximum to compile from source, unless impossible.

In my case, it's impossible for me to install Windows Build tools on a Production VM. So I must compiled outside Prod then install it there.

To download wheels, go to the [Releases](https://github.com/micha102/mod_wsgi-windows/releases) section.
