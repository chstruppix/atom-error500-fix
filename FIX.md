

YOU SHOULD CHECK OUT THE OFFICIAL ISSUE TICKET OPENED ON ATOM'S OFFICIAL GITHUB FOR ERRORS LIKE THIS, IF THE COMMON WORKAROUND PROVIDED HERE DOESN'T WORK.
https://github.com/atom/atom/issues/25417
https://github.com/atom/atom/issues/25417
https://github.com/atom/atom/issues/25417

**Note: This fix shas been tested for Atom v 1.60.0, but should work for other versions as well, if the error is similar.**


Hola Amigos!

You're here because Atom, the hackable text editor, is terrible in terms of installation of packages.

All you want to do is install a package in Atom, for ex. Hydrogen, and you've looked for hours but can't seem to find a way to install it, as none of the methods you've tried seem to beworking.


• You are unable to download the specific package from the built-in Atom Package/Theme Installer.
• After some research, you discovered a new method- 'apm install <package>'. However, that does not seem to work for you as well. 
• After headaches and a total mood-buster experience, you tend to think of giving up on coding itself, because you start questioning yourself- 'I can't even set up an IDE, how will I code!' 
• Your inner curiosity seems to maintain it's stability. Or, you're not new to coding and know things can get worse. This is nothing compared to some situations you've been in, pertaining to the errors you've come across while coding.
  

Because of the minimal popularity of this repo, you come across this repo substantially late.

Hopefully, you've come to the right place, and I can finally free you from the tight situation a meant-to-be-simple text editor has placed you in.

So the errors you are facing are-
  
  
On the text editor 'Atom', 
![](https://github.com/chstruppix/atom-error500-fix/blob/main/images/anError2.png)
  
  
  On trying 'apm' on Windows CMD,
![](https://github.com/chstruppix/atom-error500-fix/blob/main/images/anError1.png)
  
  
  You may try-
![](https://github.com/chstruppix/atom-error500-fix/blob/main/images/anError3.png)
  

  
  Okay, so what's the fix, you ask?
  Well, this specific error can strike due to a few reasons. I'll list 2 common ones here (along with fixes), and provide a link as reference to further work-aroundsif this doesn't work.
  
  
  First, it might be a problem with npm's configurations. To fix this, you may go your local users' folder on your Windows' default drive, under 'This PC'. Then go to the '.atom' folder. The location should resemble this- C:\Users\<UrMainUser>\.atom
  Once you're there, delete the 'packagelock.js' file. Then, on your terminal, try installing the required package through amp again. Note that both steps must be done in immediate succession.
  ![](https://github.com/chstruppix/atom-error500-fix/blob/main/images/anError4.png)
  
  
![](https://github.com/chstruppix/atom-error500-fix/blob/main/images/anError5.png)

  
![](https://github.com/chstruppix/atom-error500-fix/blob/main/images/anError6.png)





