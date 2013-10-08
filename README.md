Going mouse-less on MAC.
=========
Trying to remove mouse from your daily routine have a few advantages.
* It makes me more productive. It keeps me more focused.
* I can work from hammock/couch/beanbag, since I don't have to reach mouse or touchpad.

Window management:
-----------------
I recommend application slate to manage your windows.
It allows me to focus on application by shortcut, resize windows, move windows between monitors and switch focus between opened windows.
Here is good intro: http://thume.ca/howto/2012/11/19/using-slate/ .
My .slate is pretty minimalistic comparing to some people settings: https://github.com/kozikow/dotfiles/blob/master/.slate
Useful option is a hint mode, which shows all open applications with letter on it.
Pressing the letter will focus on application. It's better than alt-tabbing through long list of applications.

Useful system wide shortcuts and settings:
------------------------------------------
* When in ANY mac application you can press "cmd+shift+?" to search through all menu items available in that app.
* Some people don't know that you can change any MAC application shortcut by going to Preferences->Keyboard->Keyboard Shortucts->Application Shortcuts.
Good thing to do is to remap "go to next tab/chat/whatever" to same shortcut, since apps tend to have different one.
* Ctrl+f2 shortcut changes focus to menu bar, so you can navigate it with arrows. For some reason sharted working for me only after I remapped it to different binding.
* Turn full keyboard access on by going to Keyboard->Keyboard Shortcuts->All Controls. Then you would be able to control any mac application prompt using your keyboard.
Space to cycle between options, space to choose highlighted option, enter to choose default option.

Launcher:
---------
I use Alfred: http://www.alfredapp.com/ .
Another alternative is QuickSilver, but I heard Alfred is better.
Options worth mentioning:
* Configure search engines. Ones I most frequently use are google,
  gmail, scala docs, jira, wiki
* Use "1p website" to launch any website and logging through 1password
* "> command" to run command in terminal
* For really frequently visited websites I have a "blank" search engine,
  which serves as bookmark. On example I just type "pulls" to open list of pull
requests
* built in calculator
* Control spotify, evernote, add remember the milk tasks, post to twitter, kill top processes, translate, change units, change currencies

Shortcat
--------
http://shortcatapp.com/ .  This application allows you to control all applications that implement accessibility using keyboard. Some use cases listed on the website:
* Switching channels in Textual
* Switching chats in Skype
* Clicking links in chat apps
* Changing settings in System Preferences
* Browsing the web in Safari
* Using apps within the iOS Simulator

Chat
----
Any mac standalone application can be controlled with shortcuts.
I use Adium, which allows me to talk with my both Facebook and Skype
contacts.

Text editor
-----------
I recommend VIM. Configuring Vim is too long topic for this post.
If you want to have pretty well configured Vim out of box I recommend this: https://github.com/square/maximum-awesome .

Browser
-------
Chrome with addon Vimium:
http://lifehacker.com/5925220/make-chrome-less-distracting-with-vimium-and-these-settings
 . Vimium doesn't work in tabs, which doesn't have anything opened yet. It sometimes conflicts with 
shortcuts in some web applications, like Gmail. If you use firefox, Vimperator have more features than 
Vimium - on example you can select text using only keyboard.

Gmail
-----
Gmail have it's own excellent set of shortcuts. Just press "?" while in gmail.

IDE
---
IDEs from IntelliJ have the best Vim compatibility plugin out of mac IDEs (I heard Visual Studio have good Vim compatibility as well) * Idea Vim. The most useful shortcut is Cmd+shift+A, which searches through all possible actions.
