## Create Ubuntu Launcher

***

***

### Create Desktop Icon

* Create a file in Desktop with:

>`touch <your_file_name>.desktop` 

* Now enter below code in that file and save it:

> `[Desktop Entry]`

> `Version=1.0`

> `Name=<Any Name>`

> `Comment=<Any Comment>`

> `Exec=bash -c "<your_command_for_execute_app>"`

> `Terminal=true`

> `Type=Application`

> `Icon=<path_for_icon>/<your_icon>.png`


***

### Create Launcher Entry
> `cp <your_file_name>.desktop /usr/share/applications`
