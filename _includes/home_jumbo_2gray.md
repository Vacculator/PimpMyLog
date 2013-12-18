*Pimp my Log* is a web app written in *PHP*. It displays server logs friendly.

Formerly named *PHP Apache Log Viewer*, it has been renamed because any kind of logs can be displayed now. Basically, you will certainly use it to view your *Apache* logs, but *nginx*, *Ruby on Rails*, *Tomcat*, *sshd*, ... too !

We are `ssh > vi | tail 2>&1 grep -f` guys but tailing log files is finished now. We want a web app tool to view logs and we want it better, prettier and faster.

*Pimp my Log* is useful too for mutualized web servers. *Chrooting* *SSH* accesses and web servers is a really boring task. While you often just want to give a *SFTP* access to your developers for code and logs. But have you really try to code with logs only available via *SFTP* or via simple *HTTP* ? :-)
