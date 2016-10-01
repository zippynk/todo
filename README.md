# todo
Get it all done

To be pronounced as the applicable word, either in English or in Spanish.

https://github.com/zippynk/todo

A command line tool for keeping track of your todo list.

Todo stores its data in the file labeled ".todo" in the user's home directory.

To use across multiple devices, running todo on a server that is commonly SSH'd into is reccomended.

Usage: `todo [COMMAND] [ARGS]`

Commands:
add: Add a reminder.<br/>
add -m: Add a reminder that will display in Shabbat mode (see below).<br/>
list: List currently-activated reminders.<br/>
listall: List all reminders.<br/>
remind: Lists currently-activated reminders, but in a more annoying way. Run this on your .bashrc and/or .profile script if you want to be automatically reminded upon loggin in.<br/>
finish: Marks a reminder as complete and deletes it. Takes 1 argument, the reminder's ID.<br/>
rename: Rename a reminder. Takes one argument, the reminder's ID.<br/>
retime: Change the time for a reminder. Takes one argument, the reminder's ID.<br/>
shabbat: Toggle Shabbat Mode, a mode for partially-observant Jews and non-Jews alike (Fully observant Jews, get off the computer), where only specifically flagged reminders will be displayed. Alternatively, provide one argument, a reminder's ID, to flip whether that reminder will display in Shabbat mode.
--help: Display these commands.

(c) Copyright 2016 Nathan Krantz-Fire (a.k.a zippynk). Some rights reserved.

todo is subject to the terms of the Mozilla Public License, v. 2.0. If a copy of the MPL was not distributed in this repository, You can obtain one at http://mozilla.org/MPL/2.0/.

