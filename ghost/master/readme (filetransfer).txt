filetransfer.dll

----------------------------------------------------------------------------------------
Utility : uploading a local file on a website or downloading a file.

----------------------------------------------------------------------------------------
Usage : It's used with FUNCTIONEX("filetransfer.dll",Arguments), you can use SAORI() instead of FUNCTIONEX() depending on your environnement.

------
The Arguments are :

Argument0 : "upload" or "download"
		If the file must be uploaded, "upload", if it's a download, "download".
Argument1 : the website URL
		The URL must be written without the protocol, so without "http://" or "https://"
Argument2 : the file path
		It can be either absolute or relative


An other argument "http" or "https" can be added as Argument1. In this case, Argument1 becomes Argument2 and Argument2 becomes Argument3.

Example : FUNCTIONEX("filetransfer.dll","http","my-website/index.php","./my_files\a_file.txt")
------

Version : 1.0
Author : Azura Levidre
		 https://azura-levidre.000webhostapp.com