# linux-initial-config
A set of scripts to make initial configurations on Ubuntu and PureOS distributions.

The following softwares will be downloaded and installed (along with the required packages):
- Brave Browser
- Atom
- PyCharm Professional
- Git
- tree
- xclip
- Anydesk (On Ubuntu)
- Telegram Desktop (On Ubuntu)

Other browsers will be removed.

The command "update" will be assigned as the combinations of the following commands:
- sudo apt update
- sudo apt full-upgrade -y
- sudo apt upgrade -y
- sudo apt autoremove -y

This command will also check for the latest version of Python. If there's a new version, it'll install it as an alternative version, and creates a venv from it in ~/qenv/.

The command "cb" can be used as an alias of "xclip -selection c". Example: "cat <file_name> | cb" will copy the contents of the file_name to the clipboard.

Terminal, Brave Browser, and PyCharm will be added to startup applications.

The command "auto-dark" sets the theme to Light/Dark according to time, and schedules one further change of theme at the next sunset/sunrise.

Various keyboard shortcuts will be added for different commands.

NOTE: The OS must have a version of Python3 installed.
