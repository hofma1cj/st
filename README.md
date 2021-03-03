# st - simple terminal

This is a fork and custom rice of the suckless [Simple Terminal](https://st.suckless.org/) with the following patches applied.

| name                     | description                                |
| ------------------------ | ------------------------------------------ |
| [alpha][alpha]           | add window transparency                    |
| [boxdraw][boxdraw]       | aesthetically pleasing box characters      |
| [clipbord][clipbord]     | conforms to Freedesktop standard clipboard |
| [font2][font2]           | allows listing multiple fallback fonts     |
| [ligatures][ligatures]   | add ligature support for fonts             |
| [scrollback][scrollback] | adds scrolling support                     |
| [w3m][w3m]               | allows rendering images in the terminal    |

[alpha]:https://st.suckless.org/patches/alpha/
[boxdraw]:https://st.suckless.org/patches/boxdraw/
[clipbord]:https://st.suckless.org/patches/clipboard/
[font2]:https://st.suckless.org/patches/font2/  
[ligatures]:https://st.suckless.org/patches/ligatures/
[scrollback]:https://st.suckless.org/patches/scrollback/
[w3m]:https://st.suckless.org/patches/w3m/

## Requirements

In order to build st you need the Xlib header files.

Default fonts are [Fira Code](https://github.com/tonsky/FiraCode) and [Hanazonono](http://fonts.jp/hanazono/).

## Installation

Enter the following command to build and install st (if
necessary as root):

    make clean install