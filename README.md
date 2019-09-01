# FTP-using-JDK
File Transfer Protocol system implemented using JDK


Steps for File Transfer:-

•	Connect to the Server
•	Set file type to be transferred to binary.
•	Create an InputStream for the local file.
•	Construct path of the remote file on the server. The path can be absolute relative to the current working directory.
•	Call one of the methods to begin file transfer. 

There are two scenarios:

Using an InputStream-based approach: this is the simplest way, since we let the system does the ins and outs. There is no additional code, just passing
the InputStream object into the appropriate method,
Using an OutputStream-based approach: this is more complex way, but more control. Typically we have to write some code that reads bytes from
the InputStream of the local file and writes those bytes into the OutputStream.

•	Logout and disconnect from the server.
