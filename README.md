# RPiSSH-AppleScript
This small AppleScript application will automatically launch a terminal window and log you in to your raspberry pi using ssh.

This AppleScript application can be mofified to fit your needs.

You can connect to your raspberry pi or nany other machine that is properly configured using ssh with this applet. 
Unfortunately AppleScript only works on MacOS.

----------------------------------------------------------------------

When you first download the .scpt or the .app file, you will nees to edit some information from the actual scrept itself.

when you download the .scpt file, you need to open it and edit the two lines of code that are commented. 
Edit the two lines shown below.

    do script "ssh username@local_ip_address" in front window -- Replace Username and local_ip_address
    do script "ssh username@public_ip_address" in front window -- Replace Username and public_ip_address
    
Once you do that, press save or export the script and thats it. 

----------------------------------------------------------------------

If you want to download and use the .app file, once you downoad it, right click on the application

    Show Package Contents> Contents> Resources> Scripts> main.scpt
    
once you open the main.scpt file,

Edit the two lines shown below.

    do script "ssh username@local_ip_address" in front window -- Replace Username and local_ip_address
    
    do script "ssh username@public_ip_address" in front window -- Replace Username and public_ip_address
    
Once you do that, press save and close the finder and you will be able to launch it as an application.

----------------------------------------------------------------------

When launching this Applet, you will be guided through simple alert styled prompts
