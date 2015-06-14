# Jeffrey Way's Theme
Jeffrey Way's theme on Laracasts. Example [here](https://laracasts.com/series/whats-new-in-laravel-5-1/episodes/2).

If you have SyncedSidebarBg enabled in Package Control, please disable that!

<img src="http://i.imgur.com/oUA3alz.png" />

## Install Themes
+ Package Control: Install Package --> Material Theme.
+ Install the Facebook Theme: https://github.com/mbixby/facebook-color-scheme

## Configure

Edit `Preferences --> Settings - User` to the following:

````
{
	"auto_complete": true,
	"auto_indent": true,
	"bold_folder_labels": true,
	"caret_style": "phase",
	"color_scheme": "Packages/facebook-color-scheme-master/Facebook.tmTheme",
	"default_encoding": "UTF-8",
	"detect_indentation": true,
	"draw_indent_guides": true,
	"draw_white_space": "none",
	"enable_tab_scrolling": false,
	"font_face": "Input",
	"font_size": 13,
	"gutter": true,
	"highlight_line": true,
	"ignored_packages":
	[
		"Vintage"
	],
	"indent_subsequent_lines": true,
	"line_numbers": false,
	"line_padding_bottom": 2,
	"line_padding_top": 2,
	"margin": 4,
	"overlay_scroll_bars": "enabled",
	"preview_on_click": false,
	"smart_indent": true,
	"tab_completion": true,
	"tab_size": 4,
	"theme": "Material-Theme-Darker.sublime-theme",
	"trim_automatic_white_space": true,
	"word_wrap": true,
	"wrap_width": 0
}
````

Edit `Material-Theme-Darker.sublime-theme`

````
[
    {
        "class": "tree_row",
        "layer0.texture": "Theme - Default/row_highlight_dark.png",
        "layer0.tint": [
            87,
            93,
            107
        ]
    },
    {
        "class": "sidebar_container",
        "layer0.opacity": 1.0,
        "color": [
            37,
            43,
            57
        ]
    },
    {
        "class": "sidebar_tree",
        "dark_content": true,
        "layer0.opacity": 1,
        "color": [
            37,
            43,
            57
        ]
    },
    {
        "class": "sidebar_label",
        "layer0.tint": [
            87,
            93,
            107
        ]
    },
    {
        "class": "sidebar_heading",
        "shadow_offset": [
            0,
            0
        ]
    },
    {
        "class": "disclosure_button_control",
        "layer0.tint": [
            87,
            93,
            107
        ],
        "layer1.tint": [
            87,
            93,
            107
        ]
    },
    {
        "class": "sidebar_heading",
        "layer0.tint": [
            127,
            133,
            147
        ]
    }
]
````

Edit the following line in `Packages --> facebook-color-scheme-master --> Facebook.tmTheme`

````
<string>
263238 - Fb background
</string>
    <key>settings</key>
    <dict>
    <key>background</key>
    <string>#263238</string>
````

## Credits
+ [mbixby](https://github.com/mbixby/facebook-color-scheme) - Facebook Theme.
+ [equinosocia](http://equinusocio.github.io/material-theme/) - Material Theme.
+ [Jeffrey Way](https://github.com/JeffreyWay).

### Important
Please contact me if I have forgotten to mention a source.
