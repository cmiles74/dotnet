.Net Core on Ubuntu 16.04 (Xenial)
===========================================

You can pull this imagee from Docker Hub.

    docker pull cmiles74/dotnet 
    
I wanted to play around with the new Microsoft SQL Server on Linux and the
command-line management tools require a newer C library than that offered on the
[official Microsoft .Net image](https://hub.docker.com/r/microsoft/dotnet/).
This image is pretty much the exact same as Microsoft's, except it's built on
top of Ubuntu 16.04 (which offers the required C library).
