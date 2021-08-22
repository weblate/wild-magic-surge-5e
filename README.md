![](https://img.shields.io/badge/Foundry-v0.7.9-informational)
![](https://img.shields.io/badge/Foundry-v0.8.9-informational)
![Latest Release Download Count](https://img.shields.io/github/downloads/johnnolan/wild-magic-surge-5e/latest/module.zip)
![Forge Installs](https://img.shields.io/badge/dynamic/json?label=Forge%20Installs&query=package.installs&suffix=%25&url=https%3A%2F%2Fforge-vtt.com%2Fapi%2Fbazaar%2Fpackage%2Fwild-magic-surge-5e&colorB=4aa94a)
[![Foundry Hub Endorsements](https://img.shields.io/endpoint?logoColor=white&url=https%3A%2F%2Fwww.foundryvtt-hub.com%2Fwp-json%2Fhubapi%2Fv1%2Fpackage%2Fwild-magic-surge-5e%2Fshield%2Fendorsements)](https://www.foundryvtt-hub.com/package/wild-magic-surge-5e/)
[![Foundry Hub Comments](https://img.shields.io/endpoint?logoColor=white&url=https%3A%2F%2Fwww.foundryvtt-hub.com%2Fwp-json%2Fhubapi%2Fv1%2Fpackage%2Fwild-magic-surge-5e%2Fshield%2Fcomments)](https://www.foundryvtt-hub.com/package/wild-magic-surge-5e/)
[![Total alerts](https://img.shields.io/lgtm/alerts/g/johnnolan/wild-magic-surge-5e.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/johnnolan/wild-magic-surge-5e/alerts/)
[![Language grade: JavaScript](https://img.shields.io/lgtm/grade/javascript/g/johnnolan/wild-magic-surge-5e.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/johnnolan/wild-magic-surge-5e/context:javascript)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/X8X354DCG)

# Wild Magic Surge 5e

This module provide various bits of functionality to help automate the `Wild Magic Surge` feat.

## Features

- Prompt to roll on a 1st level or higher spell slot used with the `Wild Magic Surge` feat
- Whisper results to GM
- Auto roll for Wild Magic Surge
- Auto roll Custom Roll Table for effect
- `Tides of Chaos` auto recharge
- Custom dice roll check for surge (default is `1d20` and a roll of `1`)
- Ability to set your own roll evaluation dependent on the spell level used

## Options


### Whisper chat results to GM

Whisper all message to the GM in case you want to be nice and fudge the rolls.

[![Whisper chat results to GM](https://raw.githubusercontent.com/johnnolan/wild-magic-surge-5e/main/images/whisper-chat.jpg)](https://raw.githubusercontent.com/johnnolan/wild-magic-surge-5e/main/images/whisper-chat.jpg)

### Auto Roll a check for Wild Magic Surge instead of just a reminder to roll

The additional option `Auto Roll for a Wild Magic Surge instead of just the prompt` will auto roll in the background for you and post the result in the Chat.

Based on your settings, it will show a prompt that a `Wild Magic Surge` has occured or not.

This message is configurable should you wish.

[![Auto Roll a check for Wild Magic Surge instead of just a reminder to roll](https://raw.githubusercontent.com/johnnolan/wild-magic-surge-5e/main/images/auto-roll-check.jpg)](https://raw.githubusercontent.com/johnnolan/wild-magic-surge-5e/main/images/auto-roll-check.jpg)

### Enable Auto Roll on a Wild Magic Surge Table

This option takes things a step further and will roll a Roll Table on a `Wild Magic Surge`.

You can configure a Custom Roll Table by replacing the default name in the settings with your own version.

[![Enable Auto Roll on a Wild Magic Surge Table](https://raw.githubusercontent.com/johnnolan/wild-magic-surge-5e/main/images/enable-auto-roll-table.jpg)](https://raw.githubusercontent.com/johnnolan/wild-magic-surge-5e/main/images/enable-auto-roll-table.jpg)

### Tides of Chaos Recharge

Another option allows you to recharge `Tides of Chaos` automatically on a `Wild Magic Surge`.

[![Tides of Chaos Recharge](https://raw.githubusercontent.com/johnnolan/wild-magic-surge-5e/main/images/tides-of-chaos.jpg)](https://raw.githubusercontent.com/johnnolan/wild-magic-surge-5e/main/images/tides-of-chaos.jpg)

### Dice Formula

Set a custom dice formula you want to roll to check for a `Wild Magic Surge`. The default is `1d20`.

[![Dice Formula](https://raw.githubusercontent.com/johnnolan/wild-magic-surge-5e/main/images/dice-formula.jpg)](https://raw.githubusercontent.com/johnnolan/wild-magic-surge-5e/main/images/dice-formula.jpg)

### The target result of the dice roll

What is the dice roll result you want to check against. The default is `1`.

[![The target result of the dice roll](https://raw.githubusercontent.com/johnnolan/wild-magic-surge-5e/main/images/target-result-dice-roll.jpg)](https://raw.githubusercontent.com/johnnolan/wild-magic-surge-5e/main/images/target-result-dice-roll.jpg)

### Roll result boolean expression

Based on the target dice roll, should the result be less/greater than or equal to the result to trigger the `Wild Magic Surge`. The default is `=`.

[![Roll result boolean expression](https://raw.githubusercontent.com/johnnolan/wild-magic-surge-5e/main/images/roll-result-boolean.jpg)](https://raw.githubusercontent.com/johnnolan/wild-magic-surge-5e/main/images/roll-result-boolean.jpg)

### Setup varying Wild Magic Surge triggers dependent on spell level

Adds the ability to set your own roll evaluation dependent on the spell level used.

For example

- A lvl 1 spell only triggers wild magic if a 1 is rolled on the d20
- A lvl 4 spell triggers if a 4 or lower is rolled
- A lvl 9 triggers if a 9 or lower is rolled

Special thanks to [Jackolas126](https://github.com/Jackolas126) for this suggestion.

[![Setup varying Wild Magic Surge triggers dependent on spell level](https://raw.githubusercontent.com/johnnolan/wild-magic-surge-5e/main/images/varying-triggers.jpg)](https://raw.githubusercontent.com/johnnolan/wild-magic-surge-5e/main/images/varying-triggers.jpg)

## Installation

To install, follow these instructions:

- Inside Foundry, select the Game Modules tab in the Configuration and Setup menu.
- Click the Install Module button and enter the following URL: `https://github.com/johnnolan/wild-magic-surge-5e/releases/latest/download/module.json`
- Click Install and wait for installation to complete.

Alternatively, use the integrated module manager in Foundry.

Foundry modules page: [https://foundryvtt.com/packages/wild-magic-surge-5e](https://foundryvtt.com/packages/wild-magic-surge-5e)

## Requirements

This module requires the `dnd5e` game system to work. Your character will also need to have a `Feat` set in their character called `Wild Magic Surge`.

## Contact

For issues, please raise a bug in Github giving as much detail as you can. I will try and fix things depending on fatherhood responsibilities [https://github.com/johnnolan/wild-magic-surge-5e/issues](https://github.com/johnnolan/wild-magic-surge-5e/issues)

You can also find me lurking around on the Foundry VTT Discord [https://discord.gg/foundryvtt](https://discord.gg/foundryvtt). My Discord Tag is `JB#2780`.

[buymeacoffee-shield]: https://raw.githubusercontent.com/johnnolan/wild-magic-surge-5e/main/images/badges/buymeacoffee.png
[buymeacoffee]: https://www.buymeacoffee.com/johnnolandev
