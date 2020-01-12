## Features

Snippets for VS Code designed to help in the creation of macros for the ATEM line of video production switchers from Blackmagic Design.

![Demo](gif_demo.gif)

## How to Use

* Install [ATEM Macro Snippets from the VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=bryceseifert.atem-macro-snippets&ssr=false#review-details).
* Create a new XML file (or alternatively, edit an XML file exported from ATEM Software Control).
* Type a property you want to add and suggestions will appear. A full list of included properties is available below.
* Select your snippet!
* Using the tab key, navigate through the snippet. There will either be dropdowns featuring select options for certain values or placeholders which you can replace entirely. Once a property is selected, the snippet will also automatically update properties that appear later in the code!
* Continue hitting the tab key and selecting or entering values until the cursor is at the end of the block.

## Included Macro Presets (Alphabetical)

* Audio Controls
    * Master Fader Gain
    * Master Fader AFV
* AUX Outputs
* Capture Still
* Color Generators
* DSK Controls
* DVE Transition Settings
* FTB (Fade to Black)
* Hyperdeck Controls
* Keys
    * On Air
    * Type
    * Fill Input
    * Key Input
    * Masks
    * Advanced Chroma Key
    * Luma Key
    * Pattern Key
    * DVE / Fly Key
* Macro Controls
    * Pause
    * User Wait
* Media Players
* Preview / Program Input
* Profiles (these are helpful when starting XML files from scratch)
    * ATEM Mini
    * ATEM 1 M/E Production Studio
    * ATEM 4 M/E Broadcast Studio
* SuperSource
* Transition Controls
    * AUTO
    * CUT
    * Direction
    * Flip/Flop
* Wipe Transition Settings

## Known Issue

Missing base profiles for some ATEM switcher models.

## Requirements

It is is recommend that you are running the [latest version of ATEM Software Control](https://www.blackmagicdesign.com/support/family/atem-live-production-switchers).

## Release Notes (1.1.0)

* Added controls for keyers including the Advanced Choma key, Luma key, and Pattern key
* Improved and added additional features for DVE / Fly keys
* Added audio controls for the Master fader
* Added Macro User Wait

## Release Notes (1.0.1)

* Updated extention metadata
* Added icon

## 1.0.0

Initial release of ATEM Macro Snippets
