```
███╗   ███╗██████╗ ██████╗ ██╗  ██╗████████╗███╗   ███╗██╗     
████╗ ████║██╔══██╗╚════██╗██║  ██║╚══██╔══╝████╗ ████║██║     
██╔████╔██║██║  ██║ █████╔╝███████║   ██║   ██╔████╔██║██║     
██║╚██╔╝██║██║  ██║██╔═══╝ ██╔══██║   ██║   ██║╚██╔╝██║██║     
██║ ╚═╝ ██║██████╔╝███████╗██║  ██║   ██║   ██║ ╚═╝ ██║███████╗
╚═╝     ╚═╝╚═════╝ ╚══════╝╚═╝  ╚═╝   ╚═╝   ╚═╝     ╚═╝╚══════╝
```
***md2html*** is a [bash](https://www.gnu.org/software/bash/) script that creates [html](https://html.spec.whatwg.org/) files with custom [css](https://www.w3.org/Style/CSS/) from a specified directory of [markdown](https://en.wikipedia.org/wiki/Markdown) files using [pandoc](https://www.pandoc.org).

## Dependencies

- pandoc 2.10.1
- bash 5.0.17(1)-release

## Installation

> Ensure [pandoc](https://www.pandoc.org/) and [bash](https://www.gnu.org/software/bash/) that meet or exceed the version numbers noted above are installed on your system.

### Clone the repo

```
git clone https://www.github.com/jsstanley/md2html.git/
```

### Create an alias to use md2html easily (optional but recommended)

In your `.bashrc` file (usually found at ~/.bashrc), add:
```
alias md2html="FULL_PATH_TO_MD2HTML"
```

Reboot your machine or run the following in the terminal:
```
. ~/.bashrc
```

You should now be able to use md2html from anywhere on the command line.

## Usage
> An example css file (`custom.css`) has been provided in this repository.

```
md2html ~/notes/md/ ~/notes/css/
```

***md2html*** requires two positional arguments:

1. The first argument specifies the directory path containing the markdown files
1. The second argument specifies the directory containing the custom css file

## License

[GNU General Public License, version 2 (GPLv2)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.txt)
