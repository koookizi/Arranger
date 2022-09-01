# Arranger
Creates a Word document of a provided arrangement from a Ultimate Guitar link.
Used for creating arrangements of songs in very short time.

# Installation
Download the 'arranger' folder and open the arranger.exe file (you can create a desktop shortcut for ease of access).

# How to use
You must complete the process in order: load > transpose > arrange > generate.
The program will not let you do any other way.

1. On the loader screen, paste in the link of the Ultimate Guitar song you would like to arrange, then hit "load". A green circle, saying "LOADED", should appear.
![image](https://user-images.githubusercontent.com/102149518/187951392-0d15d6aa-5292-4cf7-b0c0-5e96ce95438d.png)

2. On the transposer screen, change the key (under current) to the current key of the song, you should be able to find it on the Ultimate Guitar page. Then select the key you would like to transpose it to (otherwise keep the "TRANSPOSE TO" key the same as the current key).
Press the "transpose" button.
This process may take some time (max. 15 seconds) as it web-scrapes from the link. You must have an internet connection. Allow any internet access.
In any case a 'chromedriverupdater.exe' command prompt terminal appears, it is so that Chromium is in the right version (used by Selenium). Ignore, and close after you are finished with the program.
IT should say "Successfully transposed" once the process is finished.
![image](https://user-images.githubusercontent.com/102149518/187952306-25bd58d7-da91-4fa5-8332-50afc6e14147.png)


3. On the arranger screen, the "PREVIEW" area is for checking what part says which (in case you haven't checked on the link already), and the "ARRANGE" area is for the arranging part.
When arranging, you can click on any arrangement part to add to the arrangement list (like a stack) and you can also remove the previously added arrangement part by pressing the "delete" button.

![image](https://user-images.githubusercontent.com/102149518/187952895-9b6f9f2f-e1e1-40de-b160-64e257694049.png)

When finished arranging, press the "apply" button.

4. On the generate screen, select a folder location for the document to be saved, then press "GENERATE".

Congrats, you have your arrangement.
