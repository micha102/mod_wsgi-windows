# mod_wsgi Windows Wheels for Apache HTTPD

Python Windows wheels for **mod_wsgi** on **Apache httpd**, compiled with **GitHub Actions**.  

The workflow automatically:

- Detects the latest **Apache HTTPD** version released by [Apache Lounge](https://www.apachelounge.com/download/).  
- Compiles **mod_wsgi** for the Python versions I select (currently **Python 3.13** and **3.14**).  
- Builds for the bitness I choose — in this case, **x64 (amd64)**.  

Thanks to [GrahamDumpleton/mod_wsgi](https://github.com/GrahamDumpleton/mod_wsgi) for the source code. Please use it and try to compile from source whenever possible.  

DON'T TRUST RANDOM BINARIES ON THE INTERNET!

> In my case, installing Windows build tools on a Production VM is impossible.  
> Therefore, I must compile outside of Production and then install the wheels there.  

To download precompiled wheels, visit the [Releases](https://github.com/micha102/mod_wsgi-windows/releases) section.
