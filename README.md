DBOTranslations
===============

Open source project to translate DBO to English.
Version 1 is only english currently.
Please contribute.

Instructions
===============

Use a program like Notepad++ to be able to read the Korean characters.

Fork our project and edit to your hearts content.
Submit a pull request and we will merge it into the working tree

It will be much faster and far more accurate translation this way.


Formatting
===============
You must follow the formatting laid out in the xml files. 

for example

		<F5>1304111</F5>
		<F6>Sprayed unreservedly to countless enemies! \nshows the essence of qigong.</F6>
		
You notice the \n in the file. this is a new line but the next section of text MUST BE right
up against it. Otherwise we end up with very strangely formatted item descriptions, etc.


Textures
===============
Textures can be edited with any image editing software
However we suggest using GIMP or Photoshop for the ability to 
patch the background when changing characters on backgrounds.


Flash
===============
Use a flash decompiler to edit the GFX files only!!!
Do not edit the swf files they are encoded using the GFX files 
during the repacking process.

suggestions for editors
FFDec
Sothink SWF Decompiler.

How to use them
===============
Once a week we will update the required client data if there were any pulls we merged.

They will be in the pack folder of  your repo.
All you have to do is drop it into your clients pack folder and run your game.
