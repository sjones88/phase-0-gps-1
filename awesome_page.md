Changes. More changes!

	
John Dees	4:10 PM
http://stackoverflow.com/questions/5343068/is-there-a-way-to-skip-password-typing-when-using-https-github
http://stackoverflow.com/questions/11889484/command-subl-from-terminal-dont-work
http://stackoverflow.com/questions/25152711/subl-command-not-working-command-not-found
ln -s "/Applications/Sublime Text 2.app/Contents/SharedSupport/bin/subl" /usr/bin/subl
sudo su
rm /usr/local/bin/subl
ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" /usr/local/bin/subl
exit
sudo ln -s "/Applications/Sublime Text 2.app/Contents/SharedSupport/bin/subl" /usr/bin/subl
open /Applications/Sublime\ Text\ 2.app/Contents/SharedSupport/bin/subl
https://gist.github.com/artero/1236170