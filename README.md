# ftpsync-php
Automatically exported from code.google.com/p/ftpsync-php
a command-line tool to synchronize local and ftp directorys

Usage: ftpsync OPTIONS FLAG file
Options could be:
-u, --user FTP login user Default is anonymous
-h, --host FTP host Default is localhost
-o, --port FTP port Default is 21
-p, --pass FTP login password Default is abc@example.com
-c, --chdir Change to such remote dir when start to sync
-r, --root Local site root Default is current working directory
-f, --sync-file Upload a single file
Flag is either:
-t, --active Turn off PASV mode
-i, --sync-incremental Upload files that newer then last upload
-a, --sync-whole-site Compare FTP files and upload newer file
