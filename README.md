# mysql.sublime-build
Sublime Text 3 Mysql Build System

Configure your login path using the followin command: 
- mysql_config_editor set --login-path=mysql-login-path --host=localhost --user=localuser --password

Then copy mysql.sublime-build to ~/.config/sublime-text-3/Packages/User

To use, on sublime select Tools->Build System->mysql

Write your query, **save it to a file** and press **CTLR+B**
