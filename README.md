# CatsiteWikiSkin
This is a fork of ScratchWikiSkin2 with the goal of fixing issues found at https://phabricator.miraheze.org/T7154.
ScratchWikiSkin2 is the default skin for the various Scratch Wikis.

## Installation
1. Download the contents of this repository and save them into $wgScriptPath/skins/CatsiteWikiSkin (a new directory)
2. Add the following line to LocalSettings.php:
```
wfLoadSkin( 'CatsiteWikiSkin' );
```
3. If desired, set $wgDefaultSkin as follows:
```
$wgDefaultSkin = 'scratchwikiskin2';
```
