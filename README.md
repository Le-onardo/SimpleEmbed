# Introduction
The SimpleEmbed extension adds the <embed> tag for embedding files. It supports remote and local (uploaded to MediaWiki) files.

This extension is based on the EmbedAll extension.

The original Author is Kim Eik
  I only edited it in order for it to work with MediaWiki Version >=1.35

# Installation
* Copy the code into a file called "SimpleEmbed.php" and place the file(s) in a directory called SimpleEmbed in your extensions/ folder.

* Add the following code at the bottom of your LocalSettings.php:
```
require_once "$IP/extensions/SimpleEmbed/SimpleEmbed.php";
```
* Navigate to Special:Version on your wiki to verify that the extension is successfully installed.

# Usage
* \<embed\>http://some.site.com/with/a/document.pdf\</embed\>
* \<embed width="250"\>Your_uploaded_document.pdf\</embed\>
## Options
* width
* height
