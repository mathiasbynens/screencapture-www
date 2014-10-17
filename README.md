Two things I like are:

* The `Command` + `Shift` + `4` shortcut for taking screenshots (OS X).
* The world wide web

So why not combine the two? This mini-project turns the screen capture
utility on OS X into a lean, mean image uploading machine.

# Install

1. `sudo mv /usr/sbin/screencapture /usr/sbin/screencapture-bin`
2. `sudo sh -c 'curl https://raw.githubusercontent.com/borismus/screencapture-www/master/screencapture > /usr/sbin/screencapture'`
3. `sudo chmod +x /usr/sbin/screencapture`

# Uninstall

1. `sudo mv /usr/sbin/screencapture-bin /usr/sbin/screencapture`
