a command-line tool to synchronize local and ftp directorys

Usage: ftpsync _OPTIONS_ _FLAG_ _file_<br>
Options could be:<br>
-u, --user              FTP login user Default is anonymous<br>
-h, --host              FTP host Default is localhost<br>
-o, --port              FTP port Default is 21<br>
-p, --pass              FTP login password Default is abc@example.com<br>
-c, --chdir             Change to such remote dir when start to sync<br>
-r, --root              Local site root Default is current working directory<br>
-f, --sync-file         Upload a single file<br>
Flag is either:<br>
-t, --active            Turn off PASV mode<br>
-i, --sync-incremental  Upload files that newer then last upload<br>
-a, --sync-whole-site   Compare FTP files and upload newer file<br>