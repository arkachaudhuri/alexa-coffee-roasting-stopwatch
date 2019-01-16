# alexa-coffee-roasting-stopwatch
An Alexa skill that helps coffee roasters record time and temperature points for sample roasts

## Starting the Skill
Enable the skill from the Alexa app, then tell Alexa:

_Alexa enable roastwatch_

## Recording A Roast
To begin recording a roast, say

_Alexa ask roastwatch to begin recording_

Alexa will then ask you a few questions:

* Roast name or sample number
* Temperature unit (ºF or ºC)

To start the roast say:

_Alexa roastwatch start_

To record a roast point, use this format:

_Alexa roastwatch <pointname> ET xxx BT yyy_

where <pointname> could be any word you say, like "charge", "aroma", "first", "second" or "drop".

For example, to record charge time/temp say:

_Alexa roastwatch charge ET 190 BT 195_

where ET is the environment temperature (optional) and BT the bean temperature.

To stop recording say

_Alexa roastwatch stop_

To hear the recorded profile say

_Alexa roastwatch readback_

## Linking to the Roastwatch service
TBD

