[Home](https://github.com/joshwhatk/sublime-text-configuration) - [Customizations](/customizations) - [Packages](/packages) - [Themes](/themes)

# SideBarEnhancements Settings

[Github](https://github.com/titoBouzout/SideBarEnhancements)

I have configured the side bar to allow me to easily open log files in Console.app.

In order for this to work as expected, the `Open With` directory needs to be placed within `/Packages/User/SideBarEnhancements`.

**Side Bar.sublime-menu**:

```
[
    {"id": "side-bar-files-open-with",
        "children":
        [

            //application 1
            {
                "caption": "Console",
                "id": "side-bar-files-open-with-console",

                "command": "side_bar_files_open_with",
                "args": {
                                    "paths": [],
                                    "application": "Console.app", // OSX
                                    "extensions":"log",  //any file with these extensions
                                    "args":[]
                                },
                "open_automatically" : false // will close the view/tab and launch the application
            },
        ]
    }
]
```
