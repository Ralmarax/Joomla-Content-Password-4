# ContentPassword Plugin for Joomla 4.xx

2023/02/17 
This is updated fork to projoomexperts fork (https://github.com/projoomexperts/Joomla-Content-Password-3) of the original plugin written by progandy (http://progandy.de/contentpassword.html).

This version is now compatible with joomla 4 (tested with joomla 4.28).

The purpose of this plugin is to password protect a joomla article.

To use this plugin.

<a href="https://github.com/Ralmarax/Joomla-Content-Password-4/archive/master.zip">Download</a>

Install it using joomla extension installer.

Go to plugins and find this plugin and enable it.

ContentPasword is activated by simple shortcode in article  {password PARAMETER }

example :  <b>{password pass="yourPa$$word" }</b>

Other parameters are 

pass = "password": sets a password

title = "title": sets the title of the password dialogue

desc = "description": sets the description of the dialogue

sql = "SQL query": sets a SQL query to verify the password. 

{password} is replaced with the entered password.

group = "group name". assigns the contribution of a group 

will contribute unlocked with a password of this group, all from this group are automatically accessible.

allowgroup = "Group Name": After successful password entry, all contributions to the specified group unlocked.

Pass Group = "Group Name": allows the activation of the contribution with the passwords of the specified group. The other contributions of the group will not be approved.

All the parameters except "title" and "desc" may be repeated and combined as often. The post will be the password entered by any parameter accepts, then unlocked.


Note: Blank passwords are not allowed and never lead to release.
