# Starving Student Millet Hybrid valve/tube headphone amplifier

## What?

A budget focussed DIY valve/tube headphone amplifier that is so simple it can be easily wired without a PCB.
This repository contains circuit schematics/diagrams for a variety of compatible valves/tubes.

![My SSMH](./simon_holywell.jpg)

## Why?

There is an amazing array of information out there on the Peter Millet designed [Starving Student Hybrid headphone amplifier][pm-ssmh] and various community modifications.
This project is an attempt to make it more easily accessible rather than requiring someone to delve into a forum thread many hundreds of pages deep.

I have drafted schematics for the circuits based around the following valves:

| Tube/Valve | Socket | Case | Schematics | Valve datasheets | Original design discussion |
|-|-|-|-|-|-|
| 12AU7 · ECC82 | Noval · B9A | glass | [PNG][12au7:png] · [PDF][12au7:pdf] · [KiCad][12au7:pro] | [Brimar][12au7:brimar] · [Tung-Sol][12au7:tung-sol] | [head-fi][12au7:head-fi] |
| 12AX7 · ECC83 | Noval · B9A | glass | [PNG][12ax7:png] · [PDF][12ax7:pdf] · [KiCad][12ax7:pro] | [Brimar][12ax7:brimar] · [Tung-Sol][12ax7:tung-sol] | [head-fi][12ax7:head-fi] |
| 12SR7 · VT-133 | octal · K8A | metal | [PNG][12sr7:png] · [PDF][12sr7:pdf] · [KiCad][12sr7:pro] | [General Electric][12sr7:ge] | [head-fi][12sr7:head-fi] |
| 12SR7GT | octal · K8A | glass | [PNG][12sr7gt:png] · [PDF][12sr7gt:pdf] · [KiCad][12sr7gt:pro] | [Tung-Sol][12sr7gt:tung-sol] | [head-fi][12sr7gt:head-fi] |
| 12SW7 | octal · K8A | metal | [PNG][12sw7:png] · [PDF][12sw7:pdf] · [KiCad][12sw7:pro] | [Tung-Sol][12SW7:tung-sol] | [head-fi][12sw7:head-fi] |
| 17EW8 · HCC85 | Noval · B9A | glass | [PNG][17ew8:png] · [PDF][17ew8:pdf] · [KiCad][17ew8:pro] | [RCA][17ew8:rca] · [Rogers][17ew8:rogers] | [head-fi][17ew8:head-fi] |
| 19J6 | mini-7 · B7G | glass | [PNG][19j6:png] · [PDF][19j6:pdf] · [KiCad][19j6:pro] | [RCA][19j6:rca] · [Tung-Sol][19j6:tung-sol] | [Peter Millet][19j6:pm] · [head-fi][19j6:head-fi] |

[12au7:png]: ./Exported%20schematics/SSMH_12A_7.png "Schematic exported as an image"
[12au7:pdf]: ./Exported%20schematics/SSMH_12A_7.pdf "Schematic exported as a PDF"
[12au7:pro]: ./KiCad%20schematics/SSMH_12A_7.pro "KiCad schematic file"
[12au7:brimar]: ./Datasheets/12AU7%20-%20Brimar.pdf "Brimar 12AU7 datasheet PDF"
[12au7:tung-sol]: ./Datasheets/12AU7%20-%20Tung-Sol.pdf "Tung-Sol 12AU7 datasheet PDF"
[12au7:head-fi]: https://www.head-fi.org/threads/millett-starving-student-hybrid-amp.319231/page-259#post-6024902 "12AU7 forum design discussion"

[12ax7:png]: ./Exported%20schematics/SSMH_12A_7.png "Schematic exported as an image"
[12ax7:pdf]: ./Exported%20schematics/SSMH_12A_7.pdf "Schematic exported as a PDF"
[12ax7:pro]: ./KiCad%20schematics/SSMH_12A_7.pro "KiCad schematic file"
[12ax7:brimar]: ./Datasheets/12AX7%20-%20Brimar.pdf "Brimar 12AX7 datasheet PDF"
[12ax7:tung-sol]: ./Datasheets/12AX7%20-%20Tung-Sol.pdf "Tung-Sol 12AX7 datasheet PDF"
[12ax7:head-fi]: https://www.head-fi.org/threads/millett-starving-student-hybrid-amp.319231/page-259#post-6024902 "12AX7 forum design discussion"

[12sr7:png]: ./Exported%20schematics/SSMH_12S_7.png "Schematic exported as an image"
[12sr7:pdf]: ./Exported%20schematics/SSMH_12S_7.pdf "Schematic exported as a PDF"
[12sr7:pro]: ./KiCad%20schematics/SSMH_12S_7.pro "KiCad schematic file"
[12sr7:ge]: ./Datasheets/12SR7%20-%20General%20Electric.pdf "General Electric 12SR7 datasheet PDF"
[12sr7:head-fi]: https://www.head-fi.org/threads/millett-starving-student-hybrid-amp.319231/post-5584511 "12SR7 forum design discussion"

[12sr7gt:png]: ./Exported%20schematics/SSMH_12S_7.png "Schematic exported as an image"
[12sr7gt:pdf]: ./Exported%20schematics/SSMH_12S_7.pdf "Schematic exported as a PDF"
[12sr7gt:pro]: ./KiCad%20schematics/SSMH_12S_7.pro "KiCad schematic file"
[12sr7gt:Tung-Sol]: ./Datasheets/12SR7GT%20-%20Tung-Sol.pdf "Tung-Sol 12SR7GT datasheet PDF"
[12sr7gt:head-fi]: https://www.head-fi.org/threads/millett-starving-student-hybrid-amp.319231/post-5584511 "12SR7GT forum design discussion"

[12sw7:png]: ./Exported%20schematics/SSMH_12S_7.png "Schematic exported as an image"
[12sw7:pdf]: ./Exported%20schematics/SSMH_12S_7.pdf "Schematic exported as a PDF"
[12sw7:pro]: ./KiCad%20schematics/SSMH_12S_7.pro "KiCad schematic file"
[12sw7:rca]: ./Datasheets/12SW7%20-%20RCA.pdf "RCA 12SW7 datasheet PDF"
[12sw7:tung-sol]: ./Datasheets/12SW7%20-%20Tung-Sol.pdf "Tung-Sol 12SW7 datasheet PDF"
[12sw7:head-fi]: https://www.head-fi.org/threads/millett-starving-student-hybrid-amp.319231/post-5584511 "12SW7 forum design discussion"

[17ew8:png]: ./Exported%20schematics/SSMH_17EW8.png "Schematic exported as an image"
[17ew8:pdf]: ./Exported%20schematics/SSMH_17EW8.pdf "Schematic exported as a PDF"
[17ew8:pro]: ./KiCad%20schematics/SSMH_17EW8.pro "KiCad schematic file"
[17ew8:rca]: ./Datasheets/17EW8%20-%20RCA.pdf "RCA 17EW8 datasheet PDF"
[17ew8:rogers]: ./Datasheets/17EW8%20-%20Rogers.pdf "Rogers 17EW8 datasheet PDF"
[17ew8:head-fi]: https://www.head-fi.org/threads/millett-starving-student-hybrid-amp.319231/post-6514939 "17EW8 forum design discussion"

[19j6:png]: ./Exported%20schematics/SSMH_19J6.png "Schematic exported as an image"
[19j6:pdf]: ./Exported%20schematics/SSMH_19J6.pdf "Schematic exported as a PDF"
[19j6:pro]: ./KiCad%20schematics/SSMH_19J6.pro "KiCad schematic file"
[19j6:rca]: ./Datasheets/19J6%20-%20RCA.pdf "RCA 19J6 datasheet PDF"
[19j6:tung-sol]: ./Datasheets/19J6%20-%20Tung-Sol.pdf "Tung-Sol 19J6 datasheet PDF"
[19j6:pm]: http://pmillett.com/starving.htm "Peter Millet design"
[19j6:head-fi]: https://www.head-fi.org/threads/millett-starving-student-hybrid-amp.319231/post-6514939 "19J6 forum design discussion"

Some of the valves share the same pin-outs, but others do not - where they do they've been shown in the same schematic.

So, for example the 12AX7 and 12AU7 have the same pin-out and power requirements so they are both included in `./KiCad schematics/SSMH_12A_7.pro`.
The same goes for the 12S_7 variants too.

[pm-ssmh]: http://pmillett.com/starving.htm

## KiCad

The diagrams were created using the open source schematic editor, [KiCad][kicad].
Whilst it can be a little complicated to learn (it doesn't take too long) it is a powerful circuit designer.

To open the project start with the `SSMH.pro` file as it should open the project and all sub-projects in KiCad - see `./KiCad schematics`.

You are then free to edit the schematic to add components or adjust values against existing components.

[kicad]: https://kicad-pcb.org/

### Handy tips

Here are a couple of handy little tips that I wish I had known when I was getting familiar with KiCad.

* <kbd>Command</kbd> + <kbd>Scrollwheel</kbd> pans the schematic horizontally (left/right)
* <kbd>Shift</kbd> + <kbd>Scrollwheel</kbd> pans the schematic vertically (up/down)

### Additional symbol/component libraries

The inbuilt valve libraries were not comprehensive enough so I made two additional symbols and used some from lib_w_vacuum.

* `19J6` by Simon Holywell (me)
* `12SR7` by Simon Holywell (me)
* `lib_w_vacuum` from http://smisioto.no-ip.org/elettronica/kicad/kicad-en.htm (please see included licence file)