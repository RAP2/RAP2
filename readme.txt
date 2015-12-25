RAP2 Project

I started working on this project since 24 November 2015. 

My intention is to learn how to create a simple game by looking at examples at (http://phaser.io/learn).

By 22 Dec 2015, I succeeded in creating instead an Educational Quiz.

I managed to play the Educational Quiz on my iphone 5S using (apple App: Cocoon Developer App).

The files in my RAP2 folder are as follows:

(1) D:\RAP2\icon.png
(2) D:\RAP2\index.html
(3) D:\RAP2\_site\js\jquery-2.0.3.min.js
(4) D:\RAP2\_site\phaser\phaser.2.4.4.min.js
(5) D:\RAP2\assets\activity.json
(6) D:\RAP2\assets\background.png
(7) D:\RAP2\assets\blackbg.png
(8) D:\RAP2\assets\blueball.png
(9) D:\RAP2\assets\button.png  
(10)D:\RAP2\assets\happychild40x60x4.png
(11)D:\RAP2\assets\instructions.png
(12)D:\RAP2\assets\ting.mp3
(13)D:\RAP2\assets\ting2.mp3
(14)D:\RAP2\img\beagle.png
(15)D:\RAP2\img\cat.png
(16)D:\RAP2\img\cheetah.png
(17)D:\RAP2\img\chipmunk.png
(18)D:\RAP2\img\dog.png
(19)D:\RAP2\img\labrador.png
(20)D:\RAP2\img\lion.png
(21)D:\RAP2\img\meerkat.png
(22)D:\RAP2\img\mouse.png
(23)D:\RAP2\img\poodle.png
(24)D:\RAP2\img\squirrel.png
(25)D:\RAP2\img\tiger.png

Details:

(1) D:\RAP2\icon.png
The Cocoon Developer App asked for this file, so I just took an icon from phaser and put it here

(2) D:\RAP2\index.html
(a) Adapted from examples in phaser: invaders, easing, audio, time, pause menu, etc. 
They were downloaded from https://github.com/ 

Some other websites: www.photonstorm.com, www.flashbynight.com/tutes/mcqquiz

(b) Initialy used Wamp(www.wampserver.com/en/) to study these examples but after changing to Windows10, 
I will ensure that the internet cable is unplugged and used the following:

Start button->Settings->search for Task(after keying in the word 'Task', need not press Enter-> Task Manager
->File->Run the command: 

C:\Program Files (x86)\Google\Chrome\Application\chrome.exe --disable-web-security  

(c) Cocoon asked for cordova.js when I tested my program using Cocoon, hence I included the statement:
         <script src="_site/cordova.js"></script> 
Apparently the file may not be required to be physically in the folder (_site) 

(d) I combined the css formating statements inside index.html as the program did not work if a separate 
main.css file is created. Maybe I still do not know how to program this part. 
 
(e) Game: User click (or touch) the screen to begin the quiz. Quiz questions appear after every 20 seconds. 
Question will also appear if the blue ball collide with any animated HappyChild on the playfield. 
Responses are marked and scores tallied. Counter (variable counter) can be set to 300 seconds (5 minutes game duration) provided
there are enough questions (>50) , otherwise, game will hang. There are only 51 questions now.   

(3) D:\RAP2\_site\js\jquery-2.0.3.min.js
Obtained from phaser examples.

(4) D:\RAP2\_site\phaser\phaser.2.4.4.min.js
Obtained from phaser examples. 

(5) D:\RAP2\assets\activity.json
This file contains the questions (text or pictures). The first option is the answer to the question. 
sources: http://geography.about.com/od/countryinformation/a/capitals.htm
www.flashbynight.com/tutes/mcqquiz

(6) D:\RAP2\assets\background.png
This picture shows a quadrangle.

(7) D:\RAP2\assets\blackbg.png
Obtained from www.flashbynight.com/tutes/mcqquiz.

(8) D:\RAP2\assets\blueball.png
Obtained from phaser time examples. 

(9) D:\RAP2\assets\button.png  
Obtained from phaser examples. 

(10)D:\RAP2\assets\happychild40x60x4.png
Modified from phaser examples. The number of happychild is set by the variable n. 

(11)D:\RAP2\assets\instructions.png
This is the Quiz starting instructions.

(12)D:\RAP2\assets\ting.mp3
Obtained from www.themotionmonkey.co.uk/free-resources/retro-arcade-sounds/phaser examples. 

(13)D:\RAP2\assets\ting2.mp3
Obtained from www.themotionmonkey.co.uk/free-resources/retro-arcade-sounds/phaser examples. 

(14)D:\RAP2\img\beagle.png
Obtained from phaser examples. 

(15)D:\RAP2\img\cat.png
Obtained from free picture websites.
 
(16)D:\RAP2\img\cheetah.png
Obtained from phaser examples. 

(17)D:\RAP2\img\chipmunk.png
Obtained from phaser examples. 

(18)D:\RAP2\img\dog.png
Obtained from free picture websites.

(19)D:\RAP2\img\labrador.png
Obtained from phaser examples. 

(20)D:\RAP2\img\lion.png
Obtained from phaser examples. 

(21)D:\RAP2\img\meerkat.png
Obtained from phaser examples. 

(22)D:\RAP2\img\mouse.png
Obtained from free picture websites.

(23)D:\RAP2\img\poodle.png
Obtained from phaser examples. 

(24)D:\RAP2\img\squirrel.png
Obtained from phaser examples. 

(25)D:\RAP2\img\tiger.png
Obtained from phaser examples.

(apple App: Cocoon Developer App - install this to your iphone - need to do a simple registration 
and provide your password). Do not install the earlier cocoon app as it will not work. 

(a) Use windows to highlight all the files and folders (index.html, icon.png, _site folder, 
assets folder, img folder) and right click mouse to send to Compressed (zipped) folder. 

Use iTunes to copy the zipped file (index.zip to the cocoon app):

Open iTunes, click device, click App, in File Sharing - select cocoon App in , scroll all the way down, click Add file 
(the index.zip file) to the App, sync the iphone.

Use iphone, click the Cocoon Developer App. Select 'Your App', click documents, ensure that your 
latest index.zip document shows up (check the date and time the document is modified). 

Click on the index.zip, click webview+, the game should appear.

If need be edit your files on your desktop and create a subequent index.zip (renaming them with 
different names like indexVer01.zip, etc) and test the file using the iphone.

Good Luck! :)

https://github.com/RAP2/RAP2.git
 
