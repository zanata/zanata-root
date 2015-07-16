Zanata
=====

Zanata is a web-based system for managing localisation projects.
Localisation (L10n) is the process of translating software or
documentation into the various local languages used around the world.

Zanata is written in Java and uses modern web technologies like JBoss,
Seam, GWT, Hibernate, and a REST API. It currently supports translation
of software through Gettext/PO, Java Properties and XLIFF (partial), and
DocBook/Publican documentation through PO files. Projects can be
uploaded to and downloaded from a Zanata server using a Maven plugin or
a Python client.

For *developers and writers*: By using Zanata for 
your document translations, you can open up your project for 
translations without opening your entire project in version 
control.

For *translators*: No need to deal with PO files, 
gettext or a version control system - just log in to the website, join 
a language team and start translating, with translation memory (history 
of similar translations) and the ability to see updates from other 
translators in seconds.


Zanata is Free software, licensed under the [LGPL][].

## How to use this super module

First git clone this module
```
git submodule init
git submodule update --checkout
```
This will check out each submodules.

[LGPL]: http://www.gnu.org/licenses/lgpl-2.1.html
