<h1 align="center">sublime_packages backups For Front-End Developer</h1>


## **Injected plug-in list**

- Package Control
- SideBarEnhancements
- Doc​Blockr
- TrailingSpaces
- **SyncedSideBar**
- Sublime Terminal
- Emmet
- HTML-CSS-JS Prettify
- Bracket Highlighter

For more nice advice, see [How to gracefully use Sublime Text](http://jeffjade.com/2015/12/15/2015-04-17-toss-sublime-text/). 

## **Preferences.sublime-settings**
If you do some of the targeted settings, she(Sublime) will be better to provide you with services, such as this（PS: You can quickly open the settings, through the shortcut keys: `Command + ,` windows: `Ctrl + ,`）:

```
{
	"folder_exclude_patterns":
	[
		".svn",
		".git",
		".hg",
		"CVS",
		"node_modules"
	],
	"font_size": 18,
	"ignored_packages":
	[
		"Vintage"
	],
	"tab_size": 2,
	"translate_tabs_to_spaces": true,
	"trim_trailing_white_space_on_save": true,
	"draw_minimap_border": true,
	"bold_folder_labels": true,
	"auto_find_in_selection": true,
	"highlight_line": true
}
```

## **Preferences.Key Bindings**

```
[
	{ "keys": ["command+\\"], "command": "toggle_side_bar" },
	{ "keys": ["command+shift+x"], "command": "toggle_comment", "args": { "block": true } },
	{ "keys": ["command+alt+p"], "command": "prompt_select_workspace" },
	{ "keys": ["command+shift+d"], "command": "delete_trailing_spaces"}
]
```

### Command Description
- toggle_side_bar: Quick Quick side bar.
- toggle_comment: Quick Quick comment.
- prompt_select_workspace: Restore Quick Switch Project shortcut.
- delete_trailing_spaces: Delete trailing spaces.
- paste_from_history: You can create key bindings composed of multiple keys.

### Additional instructions
You can create key bindings composed of multiple keys.  Like this:
```
{ "keys": ["ctrl+k", "ctrl+v"], "command": "paste_from_history" }
```

When you use this combination configuration, you have to press `Ctrl + K` first, then release `K`（or not）, and finally press `V`.

Of course, if you are using **Windows**, you should replace the `command` with `ctrl`, For more nice advice, see [How to gracefully use Sublime Text](http://jeffjade.com/2015/12/15/2015-04-17-toss-sublime-text/).
