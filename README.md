Snipplr is a Sublime Text 2 package which is used to upload and download snippets from snipplr.com.

## Installation

### With Package Control

If you have the Package Control package installed, you can install Snipplr from inside Sublime Text itself. Open the Command Palette and select "Package Control: Install Package", then search for Snipplr and you're done!

### Without Package Control

Go to your Sublime Text 2 Packages directory and clone the repository using the command below:

git clone https://github.com/jonasdp/Snipplr.git Snipplr  
Don't forget to keep updating it, though!

### Without Git

Download the latest version from the tags page. Unzip to your Sublime Text Packages folder (you can find this by opening ST2 and selecting Preferences -> Browse Packages...). You may need to rename the folder from the default to Snipplr. That's it -- you shouldn't even need to restart ST2.

## Usage
In order for package to work you need to insert your API-key from snipplr.com in the snipplr.sublime-settings file.

`  
{  
  "api_key": ""  
}  
`
 
Below are some examples of what the package does. Note that there are no menu items to trigger Snipplr but there are keyboard shortcuts to trigger upload or download(search your snippets).

Pressing ctrl+alt+p will open a textfield where you can search and insert your snippets from snipplr.com. If you select something in Sublime you can press ctrl+alt+u to upload your snippet. If you want to change the keyboard shortcuts edit the keymap-file for your OS.

`  
[  
  {  
    "keys": ["ctrl+alt+p"], "command": "snipplr_insert"  
  },  
  {  
    "keys": ["ctrl+alt+u"], "command": "snipplr_upload"  
  }  
]  
`

A SPECIAL THANKS TO JOHANNES WHO ARE THE DEVELOPER OF THIS PACKAGE!!!