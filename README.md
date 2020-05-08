# serial2pty

Creates a device under /dev/pts/ that is connected to the serial
device of a simulated mote. Thus you can use existing programs
to communicate with the serial device of a mote.
The plugin runs as normal user, so no root privileges are necessary.

If you have questions, feel free to drop me a mail: 
serial2pty OBVIOUS_SIGN frimberger.de


## INSTALL
- Execute `git clone` in `cooja/apps/`
- Rename folder to "serial2pty" (command: `mv cooja-serial2pty serial2pty`)
- run `ant jar`
- Cooja: add project path under Settings -> Cooja Projects
- Have fun!
