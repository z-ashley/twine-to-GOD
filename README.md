# twine-to-GOD
A [jq](https://stedolan.github.io/jq/) script that converts [Twine](https://twinery.org) json files into the json format for [Godot Open Dialogue](https://bitbucket.org/jsena42/godot-open-dialogue).

## Instructions
1. Download [jq](https://stedolan.github.io/jq/download/). 
2. Write your text in Twine in Sugarcube format. Export the file in [Twison format](https://github.com/lazerwalker/twison). 
3. Make a json file with the Twison output. To make a json file, you can copy-paste the output into [jsoneditoronline.org](jsoneditoronline.org) and download the json file. Place the json file in your user folder (C:\Users\Username). 
4. Copy paste the [script](https://github.com/ashleyz-hchs/twine-to-GOD/blob/master/TwineToGOD.ps1).
  Replace ```TwisonOutput.json``` with the name of the file you made in step 3, and replace ```GODFormattedFile.json``` with the name of the file you'd like to name the formatted output. 
