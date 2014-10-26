Takao fonts for powerline
===========================

It is a converted Takao font for power-line.

Takao Fonts
=============

[Takao Fonts](https://launchpad.net/takao-fonts)

Licenses
==========

[IPA Font License(IPA)](http://opensource.org/licenses/ipafont.html)

How to Use
===========

Install your PC this font.

Hot to Create this font
========================

1. Install **Takao Fonts**
--------------------------

[Takao Fonts](https://launchpad.net/takao-fonts)

2. Install **vim-powerline** (for use fontpatcher)
--------------------------------------------------

```sh
# Install powerline-fontpatcher
git clone https://github.com/Lokaltog/vim-powerline.git
```

3. Install **fontforge**
--------------------------

```sh
# Mac
brew install fontforge
```

4. Convert
--------------

```sh
cd vim-powerline/fontpatcher
fontforge -lang=py -script fontpatcher TakaoGothic.ttf
```
