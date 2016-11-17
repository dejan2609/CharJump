## CharJump

A plugin for quickly jumping to any visible character in the active document.

Inspired by and similar to https://github.com/johnlindquist/AceJump, but with a stronger focus on
making jumping to a specific character/position as easy as possible.

Should work in all editors based on the Intellij platform. 
Install by searching for "CharJump" in the Plugins dialog, or unzip a
[distribution](https://github.com/jpmossin/charjump/releases) into your plugins folder 
(e.g ~/.IntelliJIdea2016.2/config/plugins/)


##### Usage
Activate with Ctrl+Comma (configurable) and enter the character for the position you wish to jump to. 
A single-character label will then be shown for each matching position in the document.

After entering a target character, the jump can be aborted by pressing Space.  

##### Development
Build with:
```
./gradlew buildPlugin
```
Start up a local sandboxed IDEA with the plugin running using: 
```
./gradlew runIdea
```