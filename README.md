# Bongs_Multi_Kitchen_Linux

Basic User Giude For Linux Version..

First Steps..
Download from one of available sources or cloned git
Extract ( anywhere should be fine just make sure to keep file\folder structure and that there are no spaces in name )
if you have cloned git repo the file should already be executable if its not then
use terminal to navigate to extracted Bongs_Kitchen folder
type chmod 755 Main ( this should make executable )
open Bong_Kitchen folder and double click Main ( click run in terminal )
Kitchen Should now be setup for use....

Main Options Menu..
At the first menu you will be given a choice to choose between the tools within the kitchen.
Option 1 Will Take you to APK Kitchen
Option 2 Will take you to the Lollipop Deodexer
Option 3 Will take you to the Rom Creation Tools ( Not Implimented Yet.. )

APK Kitchen Guide..
on first run of the APK Kitchen it will take you to the setup page to set the folders needed,
and pull framework files from phone option
you can then install you framework files from there, there are all stored within Bongs_Kitchen/tools/framework/apktoolversion
most current version of apktool is set as default but can be changed
for those that do change apktool there is a fast framework install option from main menu,
then it is just a case of dropping apk or jar you want to edit in "place_input_files_here" folder
then decompile\extract depending on what you need to do,
do your edits and recompile\re-zip,
if its a system app make sure to do a system compile to keep original signature
put edit file on phone and test.

smali\baksmali are included as options for those like me who sometimes extract a file
to do some basic edits but then want to do some smali edits without having to do a
full decompile again and overwrite/loose there already edited files.

Lollipop Deodexer Guide..
First step is to copy your full rom folder over into the main kitchen folder. ( Ensure there are no spaces in folder name )
Start Bongs Multi Kitchen ( Double Click Main )
Select option 2 at first menu to goto the Deodexer menu
Select option 1 at next menu
Type the name of your Rom folder exactly as it is in the Kitchen ( If this step is done correctly your rom info should be shown on the right )
If everything looks correct select option 2 and then option 4 for a full system deodex
Sit back and wait for it to finish
Test the rom on your phone.

Rom Tools Guide..
Not intergrated by developer yet..
