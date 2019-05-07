# CSGO-Syntax-Sublime-Text
CSGO Syntax highlighting for Sublime Text 3

## About
If you find any problems with the package or got any suggestions, please open an issue [here](https://github.com/kvishno/CSGO-Syntax-Sublime-Text/issues) (contributions are also more than welcome). Some Cvars might be missing, as they are updated constantly. 

This package will also have basic compatibility with other source based games, as many Cvars are universal. It won't be perfect as some Cvars/weapons are game specific, but it will fulfill most needs.

## Installation
* Place `csgo_syntax.*` files in `\..\Sublime Text 3\Data\Packages\User` and pick CSGO.cfg as syntax under View
* Alternatively install [PackageDev](https://github.com/SublimeText/PackageDev), place the [csgo_syntax.YAML-tmLanguage](https://raw.githubusercontent.com/kvishno/CSGO-Syntax-Sublime-Text/master/csgo_syntax.YAML-tmLanguage) file in `\..\Sublime Text 3\Data\Packages\User`, then open the file in Sublime and press F7 to build 

## To-do
* Completions Files
* Other common source game compatibility (TF2, CSS, Dota2, etc.)
* Clean-up in Cvars (more regex, dupes in functions and Cvars)
* Improved matching and highlighting

## Example highlighting in a config
![Image of highlighting](https://raw.githubusercontent.com/kvishno/CSGO-Syntax-Sublime-Text/master/images/csgosyntaximage1.png)

---

With inspiration from  [/u/kamikaze_algazi](https://www.reddit.com/r/GlobalOffensive/comments/bl9qz9/csgo_config_file_syntax_highlighting/)  and [@Janzzze](https://github.com/Janzzze/csgo-sublime-syntax/) 
