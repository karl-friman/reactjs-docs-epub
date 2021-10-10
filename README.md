# reactjs-docs-epub

Epub format React Js Docs (Aug 29th 2021)

Built these docs using [this tool](https://gist.github.com/sebastianrothbucher/e2b82202432657052d6d56bd30bfe6d2). 

I use the Bash mode of the console emulator [Cmdr](https://cmder.net/). 
```console
pandoc *.md > All.html
```
After that you can either create the TOC using [Calibre](https://calibre-ebook.com/) or let Pandoc do it using 
```console
pandoc --toc All.html > Book.epub
```
