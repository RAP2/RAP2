RAP2 Project

I started working on this project since 24 November 2015. 

My intention is to learn how to create a simple game by looking at examples at (http://phaser.io/learn).

By 22 Dec 2015, I succeeded in creating instead an Educational Quiz.

I managed to play the Educational Quiz on my iphone 5S using (apple App: Cocoon Developer App).

The files in my RAP folder are as follows:

(1) D:\RAP\icon.png
(2) D:\RAP\index.html
(3) D:\RAP\_site\js\jquery-2.0.3.min.js
(4) D:\RAP\_site\phaser\phaser.2.4.4.min.js
(5) D:\RAP\assets\activity.json
(6) D:\RAP\assets\background.png
(7) D:\RAP\assets\blackbg.png
(8) D:\RAP\assets\blueball.png
(9) D:\RAP\assets\button.png  
(10)D:\RAP\assets\happychild40x60x4.png
(11)D:\RAP\assets\instructions.png
(12)D:\RAP\assets\ting.mp3
(13)D:\RAP\assets\ting2.mp3
(14)D:\RAP\img\beagle.png
(15)D:\RAP\img\cat.png
(16)D:\RAP\img\cheetah.png
(17)D:\RAP\img\chipmunk.png
(18)D:\RAP\img\dog.png
(19)D:\RAP\img\labrador.png
(20)D:\RAP\img\lion.png
(21)D:\RAP\img\meerkat.png
(22)D:\RAP\img\mouse.png
(23)D:\RAP\img\poodle.png
(24)D:\RAP\img\squirrel.png
(25)D:\RAP\img\tiger.png

Details:

(1) D:\RAP\icon.png
The Cocoon Developer App asked for this file, so I just took an icon from phaser and put it here

(2) D:\RAP\index.html
(a) Adapted from examples in phaser: invaders, easing, audio, time, pause menu, etc. They were downloaded from https://github.com/ 

Some other websites: www.photonstorm.com, www.flashbynight.com/tutes/mcqquiz

(b) Initialy used Wamp(www.wampserver.com/en/) to study these examples but after changing to Windows10, I will unplug my cable and used the following:

Start button->Settings->search for Task(after keying in the work 'Task', need not press Enter-> Task Manager->File->Run the command: 

C:\Program Files (x86)\Google\Chrome\Application\chrome.exe --disable-web-security  

(c) Cocoon asked for cordova.js when I tested my program using Cocoon, hence I included the statement:
         <script src="_site/cordova.js"></script> 
Apparently the file may not be required to be physically in the folder (_site) 

(d) I combined the css formating statements inside index.html as the program did not work if a separate main.css file is created. Maybe I still do not know how to program this part. 
 
(e) Game: User click (or touch) the screen to begin the quiz. Quiz questions appear after every 20 seconds. Question will also appear if the blue ball collide with any animated HappyChild on the playfield. Responses are marked and scores tallied. Counter can be set to 600 seconds (5 minutes game duration) provided  there are enough questions (>50) , otherwise, game will hang.  

(3) D:\RAP\_site\js\jquery-2.0.3.min.js
Obtained from phaser examples.

(4) D:\RAP\_site\phaser\phaser.2.4.4.min.js
Obtained from phaser examples. 

(5) D:\RAP\assets\activity.json
This file contains the questions (text or pictures).

(6) D:\RAP\assets\background.png
This picture shows a quadrangle.

(7) D:\RAP\assets\blackbg.png
Obtained from www.flashbynight.com/tutes/mcqquiz.

(8) D:\RAP\assets\blueball.png
Obtained from phaser time examples. 

(9) D:\RAP\assets\button.png  
Obtained from phaser examples. 

(10)D:\RAP\assets\happychild40x60x4.png
Modified from phaser examples. 

(11)D:\RAP\assets\instructions.png
This is the Quiz starting instructions.

(12)D:\RAP\assets\ting.mp3
Obtained from www.themotionmonkey.co.uk/free-resources/retro-arcade-sounds/phaser examples. 

(13)D:\RAP\assets\ting2.mp3
Obtained from www.themotionmonkey.co.uk/free-resources/retro-arcade-sounds/phaser examples. 

(14)D:\RAP\img\beagle.png
Obtained from phaser examples. 

(15)D:\RAP\img\cat.png
Obtained from free picture websites.
 
(16)D:\RAP\img\cheetah.png
Obtained from phaser examples. 

(17)D:\RAP\img\chipmunk.png
Obtained from phaser examples. 

(18)D:\RAP\img\dog.png
Obtained from free picture websites.

(19)D:\RAP\img\labrador.png
Obtained from phaser examples. 

(20)D:\RAP\img\lion.png
Obtained from phaser examples. 

(21)D:\RAP\img\meerkat.png
Obtained from phaser examples. 

(22)D:\RAP\img\mouse.png
Obtained from free picture websites.

(23)D:\RAP\img\poodle.png
Obtained from phaser examples. 

(24)D:\RAP\img\squirrel.png
Obtained from phaser examples. 

(25)D:\RAP\img\tiger.png
Obtained from phaser examples.

(apple App: Cocoon Developer App - install this to your iphone - need to do a simple registration and provide your password). Do not install the earlier cocoon app as it will not work. 

(a) Use windows to highlight all the files and folders (index.html, icon.png, _site folder, assets folder, img folder) and right click mouse to send to Compressed (zipped) folder. 

Use iTunes to copy the zipped file (index.zip to the cocoon app):

Open iTunes, click device, click App, select cocoon App, scroll all the way down, Add file (the index.zip file) to the App, sync the iphone.

Use iphone, click the Cocoon Developer App. Select 'Your App', click documents, ensure that your latest index.zip document shows up (check the date and time the document is modified). 

Click on the index.zip, click webview+, the game should appear.

If need be edit your files on your desktop and create a subequent index.zip (renaming them with different names like indexVer01.zip, etc) and test the file using the iphone.

Good Luck! :)
