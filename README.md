# Create Google Meet
Opens a new Google Meet and copies the URL to the clipboard

## Installation
Just download the zip [here](https://github.com/davidwebca/alfred-create-google-meet/blob/master/Create%20Google%20Meet.alfredworkflow?raw=true) and open the worfklow file with Alfred.

## Instructions
Type ```meet``` and hit enter.

## Details
The URL to create a new Google Meet is https://meet.google.com/new. Once the JavaScript of the web page kicks in, the proper URL gets generated in the browser, so we need to wait for it to be done. The easiest way to do that is to simply copy the URL to the clipboard until it changes. This is done through Apple Script instructions that allow any browser to be set as default as long as they support CMD + L to select the current tab's address and CMD + C to copy to the clipboard.
