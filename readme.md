JPEGrescan plugin for Adobe Photoshop Lightroom
===============================================

Lightroom plugin by Jarno Heikkinen <info@capturemonkey.com>  
Based on jpegrescan by Loren Merritt  


Introduction
------------

This is a simple Lightroom export plugin, which attempts to reduce JPEG files
by using different lossless compression parameters on the exported file.

Currently, only 64-bit Mac OS X is supported; I don't have a working Windows environment 
available for development or testing (jpegrescan requires Perl and jpegtran) 

Simply install the plugin and add the export filter in the Lightroom's export dialog.
In the export settings, you can also optionally set removal of _ALL_ metadata, including
ICC profiles and such.

You can also see some byte statistics in the plugin manager.

