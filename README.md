# Welcome

I used to be a developer. I still do some programming for personal purposes.

## Utilities

I have written several utilities for myself and have deemed some of them good enough to publish online:

* A DjVu to PDF converter called [`dpsprep`](https://github.com/kcroker/dpsprep) (not initially my own, but I am the sole maintainer after my rewrite).
* My take at extended file attributes called [`viat`](https://github.com/v--/viat) (**vi**rtual **at**tributes).
* My `dmenu` twist called [`searchtool-gtk`](https://github.com/v--/searchtool-gtk).
* A TeX-to-unicode input method helper called [`unicodeit-gtk`](https://github.com/v--/unicodeit-gtk).
* A management tool for [pacman repositories](https://pacman.archlinux.page/) called [`alrin`](https://github.com/v--/alrin) (**A**rch **L**inux **r**epository for [**i**vasilev.**n**et](https://ivasilev.net)).

## Notes

I have published some notes related to mathematics:

* My personal [`notebook`](https://github.com/v--/notebook) contains mostly math and algorithmic code, but also has some tools for working with LaTeX and BibLaTeX. At some point big text documents start requiring customized tools.
* Some folks from Bulgaria find my state examination note repository [`se2018`](https://github.com/v--/se2018) useful.

## Demos

I have also published a few repositories for demonstrative purposes:

* For my [website](https://ivasilev.net) ([repository](https://github.com/v--/website)), I have implemented some things that are usually handled by libraries - observables, reactive rendering, type-based schemas, abstract rich text, etc. It was a useful learning experience and I believe the code is concise enough to be useful as a reference.
* I have shared some Jupyter notebooks in a repository called [`244`](https://github.com/v--/244) (the name is a UNIX permission pun).
* After digitizing several books, my process evolved into what I describe in the [`digitization-demo`](https://github.com/v--/digitization-demo) repository.
* In a university course on mathematical modeling, I created a simulation for neural impulses called [`neuronsim`](https://github.com/v--/neuronsim).
* I outline my dotfile management and my bibliography management scripts in my [Viat usage examples](https://github.com/v--/viat/blob/master/examples).

## Unmaintained

Finally, the following are obsolete (for me) and thus unmaintained:

> [!NOTE]
> I still accept pull requests and, if necessary, I can do a small fix.

* A X11 focus toggling tool called [`wintoggle`](https://github.com/v--/wintoggle).
* A library called [`subscribed`](https://github.com/v--/subscribed) that I developed for my `neuronsim` simulation. Ironically, I rewrote both since their inception in 2015 and now they are independent.

## The peculiar case of my username

I chose my GitHub handle, `v--`, after trying a few other short strings in late 2013. It has since then become invalid.

I don't care enough to change it, however I will describe how my username mostly prevents me from using GitHub Pages. To quote [RFC 952](https://www.rfc-editor.org/rfc/rfc952):

> The last character [of a host name] must not be a minus sign or period.

Thus, `v--.github.io/<project-name>` is technically invalid. Nevertheless, for some older (pre-2016) repositories, GitHub allows me to use Pages - see <https://v--.github.io/subscribed/>. The same possibly holds for the [GitHub container registry](https://ghcr.io) (although I have no intention to try).

> [!NOTE]
> GitHub Pages is undoubtedly useful for project documentation, but even in my limited experience, it requires more manual setup compared to, say, [Read the Docs](https://readthedocs.com), which even provides some niceties like multiple documentation versions out-of-the-box.
