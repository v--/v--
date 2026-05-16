# Welcome

I used to be a developer. I still do some programming for personal purposes.

* I have written several utilities for myself and deemed some of them good enough to publish online:
  * A DjVu to PDF convertor called [`dpsprep`](https://github.com/kcroker/dpsprep) (not initially my own, but I am the sole maintainer after my rewrite).
  * My take at extended file attribute called [`viat`](./viat) (**vi**rtual **at**tributes).
  * My own `dmenu` twist called [`searchtool-gtk`](./searchtool-gtk).
  * A TeX-to-unicode input method helper called [`unicodeit-gtk`](./unicodeit-gtk).
  * An older X11 focus toggling tool called [`wintoggle`](./wintoggle).
  * An older library called [`subscribed`](./subscribed) that I developed for my neuronsim simulation (see below). Ironically, I rewrote both since their inception in 2015 and now they are independent.

* I have published some notes related to mathematics:
  * My personal [`notebook`](./notebook) contains mostly math and algorithmic code, but also has some tools for working with LaTeX and BibLaTeX. At some point big text documents start requiring customized tools.
  * Some folks from Bulgaria find my state examination notes repo [`se2018`](./se2018) useful.

* I have published a few repositories for demonstrational purposes:
  * For my [`website`](https://ivasilev.net) ([repo](./website)), I have implemented some things like observables, reactive rendering, type-based schemas, abstract rich text, translation, etc. It was a useful learning experience and I believe the code is concise enough to be useful as a reference.
  * I have shared some Jupyter notebooks in a repo called [`244`](./244) (the name is a UNIX permission pun).
  * After digitizing several books, I have developed my own process, which is described in the [`digitization-demo`](./digitization-demo) repo.
  * For a university course on mathematical modeling, I have created an unpretentious simulation for neural impulses called [`neuronsim`](./neuronsim).

* The other repositories are either one-off forks, university course exercises or hackathon projects.

## The peculiar case of my username

I chose my GitHub handle, `v--`, after trying a few other short strings in late 2013. It has since then become invalid.

I don't care enough to change it, however I will describe how my username mostly prevents me from using GitHub Pages. To quote [RFC 952](https://www.rfc-editor.org/rfc/rfc952):

> The last character [of a host name] must not be a minus sign or period.

Thus, `v--.github.io/<project-name>` is technically invalid. Nevertheless, for some older (pre-2016) repositories, GitHub allows me to use Pages - see <https://v--.github.io/subscribed/>. The same possibly holds for the [GitHub container registry](https://ghcr.io) (although I have no intention to try).


> ![NOTE]
> Even though GitHub Pages are useful for documentation, [Read the Docs](https://readthedocs.com) provides some niceties like multiple documentation versions out-of-the-box.


