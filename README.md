https://user-images.githubusercontent.com/81305164/152664895-8c1ad584-eea9-4cb2-8baa-4c27c09eb8a3.mp4

# manga-cli

A Bash script for reading mangas via the terminal by scraping [Mangakakalot](https://mangakakalot.com/).
Totally based and forked from 7USTIN's manga-cli

## Table of Contents

- [Usage](#Usage)
- [Install](#Installation)
- [Dependencies](#Dependencies)
- [Preview](./preview.mp4)
- [Disclaimer](./DISCLAIMER.md)
- [License](./LICENSE.md)

## Usage

```text
A Bash script for reading mangas via the terminal

Usage:
	./manga-cli [Option] [Manga Name]

Options:
	-h, --help		Print this help page
	-V, --version		Print version number
	-u, --update		Fetch latest version from the Github repository
	-l, --last-session    Open last session
	-c, --cache-size	Print cache size ($HOME/.cache/manga-cli)
	-C, --clear-cache	Clear cache ($HOME/.cache/manga-cli)
```

## Install

Install dependencies [(See below)](#Dependencies)

### Linux

```sh
git clone https://github.com/stl3/manga-cli && cd manga-cli
sudo cp manga-cli /usr/local/bin/manga-cli
```

### img2pdf

On a Debian- and Ubuntu-based systems, img2pdf can be installed from the official repositories:

`$ apt install img2pdf`

If you want to install it using pip, you can run:

`$ pip3 install img2pdf`

If you prefer to install from source code use:

`$ cd img2pdf/
$ pip3 install .`


## Dependencies

- cat
- curl
- sed
- awk
- tr
- find
- xargs
- sort
- du
- git
- diff
- patch
- img2pdf
- zathura
