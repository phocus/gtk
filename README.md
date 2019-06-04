# Phocus GTK3 Theme
This GTK3 theme is part of the [Phocus](https://github.com/phocus) theme collection.

## Installation

### Arch
```bash
$ yay -S phocus-gtk-theme-git
```

### From source
Make sure to install the following dependency:

- npm

Clone the phocus/gtk repository:

```bash
$ git clone https://github.com/phocus/gtk.git phocus-gtk
```

And finally install using make:

```bash
$ cd phocus-gtk
$ make
$ sudo make install
```

## Development
To make development as easy as possible, clone the repository into your users themes directory and install the node dependencies:

```bash
$ git clone https://github.com/phocus/gtk.git ~/themes/phocus
$ npm install
```

### Build
To build the theme, run:
```bash
$ cd ~/themes/phocus
$ npm run build
```

### Build with file-watcher
To start a file-watcher that builds automatically every time you update a file:
```bash
$ cd ~/themes/phocus
$ npm run watch
```
