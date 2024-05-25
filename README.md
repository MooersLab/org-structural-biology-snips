![Version](https://img.shields.io/static/v1?label=org-structural-biology-snips&message=0.0&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

# Structural biology snippets for org-mode (coming soon)

We are developing the org-structural-biology-snips library to support polyglot literate programming.
Literate programming supports reproducible research by interleaving explanatory text, computer code, and computer output in the same document.
Polyglot programming involves the use of multiple programming languages in one document.
Most structural biology workflows involve the use of multiple software packages that are often written in several programming languages.
The data are often too large to be directly incorporated into a single document, so literate programming of the entire workflow is not realistic now.
Nonetheless, it is important to apply literate programming to amenable workflow segments to improve the rigor of today's research.

Org is one of the most advanced, easy-to-use, and best-documented platforms that supports polyglot programming.
Org is a powerful markup language with an easy-to-understand syntax.
It combines the support for literate programming with support for project planning via org-agenda.
Most users of Emacs spend much of their time using Org.
Org is deployed as a major mode called org-mode.
Org-mode has been under development since 2003 and has a number of minor modes that start with org and extend its capabilities.

Org is best written in the Emacs editor, but it can also be written in several other popular text editors, such as Visual Studio Code.
Contrary to a popular misconception, using Emacs does not require knowledge of elisp or keybindings; all necessary commands are available from pulldown menus that resemble pulldown menus.
While Emacs can be run in the terminal, most users use a stand-alone GUI application that provides a user interface familiar to other text editors.

Emacs originated in 1976, but it has undergone continual revision and [[https://www.emacswiki.org/emacs/EmacsHistory][updating]].
A cadre of hundreds of expert developers maintains the core of Emacs, while thousands of contributors have built packages like Org to extend Emacs. 
A group of young users has exhibited exceptional leadership over the past decade by organizing and hosting the annual virtual emacs conference.
Videos of past talks are available online.
Three users of particular note are as follows:

  Dave Wilson has supplied scores of instructional videos for novice and advanced beginners as part of his System-Crafters podcast.
  - Sacha Chau writes concise, thoughtful blog posts and well-written distillations accessible to beginners. She also supplies a weekly summary of noteworthy developments.
  - (Prot) is a Greek philosopher living in the mountains of rural Cyprus who started using Emacs only several years ago and has become an expert user without formal computer science training. He has a series of thought-provoking videos on YouTube about Emacs and leading a self-reliant life.
  
Many other users have provided helpful tutorial videos on YouTube.
According to the Lindy Effect or Law, the amount of time a technology has been in use is a good predictor of its future existence.
In 2022, we can expect Emacs to be in use until 2068.
As one of the oldest text editors still in use, Emacs is one the safest editors to invest effort into mastering.
So is Vim, which arose at about the same time, but, unlike Vim, Emacs offers so many capabilities beyond text editing that it is more of a computing environment (it is almost an operating system). 
  
Code blocks in org-mode can access various programming compilers or interpreters directly or indirectly by calling Jupyter notebook kernels for various structural biology software.
The latter are easy to set up if the software is wrapped in Python.

## Update history

|Version      | Changes                                                                                                                                    | Date                 |
|:-----------:|:------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------:|
| Version 0.0 |   Added badges, funding, and update table.                                                                                                 | 2024 May 24         |

## Sources of funding

- NIH: R01 CA242845
- NIH: R01 AI088011
- NIH: P30 CA225520 (PI: R. Mannel)
- NIH: P20 GM103640 and P30 GM145423 (PI: A. West)

