# bashrc_settings

I will collect some custom commands for the Linux/Ubuntu Server Setup.

For the beginning there are primarily commands to customize the command promt and color codes in the ls command.
Additionally there is an alias for pwd and ls in combination and a PATH extension to look for executable files.


use:

wget -qO- https://raw.githubusercontent.com/dalistra/linuxserver/main/bashrc/V3 >> TEXTFILENAME

if you want to add the text directly to ".bashrc" in $HOME use:

wget -qO- https://raw.githubusercontent.com/dalistra/linuxserver/main/bashrc/V3 >> /home/USERNAME/.bashrc

to pull the text to your server

if you just want to see the text in the console use (the new lines are lost in this process, so it is a one liner :( ... )

echo $(wget -qO- "https://raw.githubusercontent.com/dalistra/linuxserver/main/bashrc/V3")


