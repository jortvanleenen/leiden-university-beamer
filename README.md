![Titlepage](example-images/slide1.png)
# Leiden University Beamer Theme
A beamer theme that aims to closely mimic [Leiden University](https://www.leidenuniversity.nl/)'s presentation slides as provided in their [house style](https://huisstijl.leidenuniv.nl/en/).

I am by no means a LaTeX expert so please, if you have any suggestions, feel free to create an issue or pull request!

## Getting Started
It is designed to easily integrate with [Overleaf](https://www.overleaf.com). This repository can be downloaded as .zip file and uploaded to Overleaf as a new project. To get started, I recommended modifying `example.tex` to your liking. 

Feel free to remove the `README.md` file and the `example-images` directory. These are only required for the text you are currently reading here on GitHub and do not affect the actual presentation in any way.

## Options
### Font
The theme is meant to be used with the Minion Pro font as in-use by the university. This font is, however, not allowed to be redistributed. If you have got access to the font yourself, you can add it to your local copy of this repository. The theme expects the font files, if present, to be in TTF format, with filenames 'Minion Pro <Regular/Bold/Italic/Bold Italic>'. If you have got a different format, the way the theme interprets font files can be changed in `beamerthemelu.sty` under font options.

### Class Option
A language can be provided to the beamer class as option, this will then get passed along to the theme. By default, the theme requires the Babel package as it allows the theme to automatically translate Leiden University's footer text. Currently, two translations are provided: one for Dutch, and English for every other set language.

### Theme Options
- `defaultfooter` if set, change the footer to display Leiden University's default message 'Discover the world at Leiden University' in Dutch or English depending on the set language (above) in the footline.
  - _Default: custom footer providing author short, institution short and title short_
  - _Option(s): none_

- `style` can be provided as an option to the theme to change the colour of the author bar on the titlepage. Currently, this option is able to take the name of every institute at Leiden University and then uses its primary colour as background for that section.
  - _Default: midblueLU (#8592BC), like the example PPTX presentation provided by Leiden University_
  - _Option(s): social, science, humanities, archaeology, fgga, medicine, law_
  
## Copyright
To this project applies the LaTeX Project Public License version 3 (LPPL Version 1.3c  2008-05-04).

## Thanks
I would like to thank @TAdeJong and @Thyrum for their initial work on an unofficial beamer theme for Leiden University and sparking my interest to come up with an altered own version!

## Additional Example Images
![Titlepage](example-images/slide2.png)
![Titlepage](example-images/slide3.png)
![Titlepage](example-images/slide4.png)
![Titlepage](example-images/slide5.png)
![Titlepage](example-images/slide6.png)
![Titlepage](example-images/slide7.png)
