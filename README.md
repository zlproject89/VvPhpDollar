# VvPhpDollar #
**Sublime Text Plugin** for a convenient way to insert PHP Dollar.

## Compatibility  ##
* Sublime Text 2
* Sublime Text 3

## Installation ##
* Install [Package Control][pck-ctrl]. Once installed, fire up the Command Palette (`Command-Shift-P` on OS X, `Ctrl-Shift-P` on Linux/Windows). Choose `Package Control: Install Package` and then select `VvPHPDollar`, when the list appears. Package Control will install `VvPHPDollar` and keep it be last version automatically .
* Download plugin's zip file from here [Github][github] to your local laptop. Once downloaded, put unzip it, then open your `Sublime Text 2 or 3`, open your menu: `Preferences` --> `Browse Packages...`, then put the unzip folder into this folder.

## Usage ##
* When you edit the file(i.e. `PHP`), when you need to put a `$` sign, you just need to input **placeholder**(i.e. `vv `, note: here is a space after`vv`), the plugin will replace this placeholder by PHP Dollar `$` sign.
* Default key-map: <kbd>ctrl+alt+l</kbd>

##  Customize ##
Edit [VvPhpDollar.sublime-settings][vv_php_dollar_settings] file
* For **placeholder**, edit `vv_sign` field.
* For **syntax**, edit `syntax_list` field.
```json
{
    "vv_sign":"vv ",
    "syntax_list":[
        "PHP"
    ]
}
```
Edit [Default.sublime-keymap][default_key_map] file
* For **key binding**
```json
[
{
    "keys":["ctrl+alt+l"],
    "comand":"vv_php_dollar"
}
]
```
[pck-ctrl]: http://wbond.net/sublime_packages/package_control "Sublime Package Control by wbond"
[github]: https://github.com/ZhaonanLi/VvPhpDollar "VvPHPDollar by Zhaonan Li"
[vv_php_dollar_settings]: VvPhpDollar.sublime-settings "VvPhpDollar.sublime-settings"
[default_key_map]: Default.sublime-keymap "Default.sublime-keymap"
