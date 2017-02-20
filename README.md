# R-Type
[Epitech Project] : 3rd Year  
Team: Raphael Thiebault, Adeline Galasso, Antoine Lempereur, Antoine Zanardi, Baptiste Cadoux, Corentin Ducatez

Synopsis
=
Make the famous multi-player shoot-em-up R-Type in C++ with a client/server architecture and cross-platform Windows/Linux. 

Required
=
SFML : Version > 2.0  
CMake : Version > 3.0   
[For windows : "SFML" directory must be located in C:/Program Files(x86)]

Compilation
=
Linux : Just execute make.sh at project's root folder.    
Windows : Execute CMake at project's root folder and then open rtype.sln with VisualStudio and build the project 

Code Example
=

Server directory
--
Usage : ./server_rtype [port]	
*port : port of communication, default is 4242*

Client directory
--
Usage : ./client_rtype [port [address]]   
*port : port of communication, default is 4242*   
*address : ip address of the server, default is 127.0.0.1*
