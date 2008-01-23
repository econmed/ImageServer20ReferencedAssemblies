The log4net.dll file is a customized version.

It uses the 1.2.10 version of the log4net software, with the patched 
FileAppender.cs file found in this directory. 

The log4net source can be downloaded with subversion from here:

http://svn.apache.org/repos/asf/logging/log4net/tags/log4net-1.2.10/

Simply replace FileAppender.cs in the src/Appender directory, and 
rebuild the library to reproduce the log4net dll file.  Note that NAnt
is used to rebuild the library with a strong name.