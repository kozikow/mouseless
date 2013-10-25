Going mouse-less on MAC.
=========
Trying to remove mouse from your daily routine have a few advantages.
* It makes me more productive. It keeps me more focused.
* I can work from hammock/couch/beanbag, since I don't have to reach mouse or touchpad.
* Not using mouse will help you reduce the risk of wrist injury: http://kellishaver.tumblr.com/post/31143579095/wrist-and-hand-pain-when-programming

Window management:
-----------------
I recommend application slate to manage your windows.
It allows me to focus on application by shortcut, resize windows, move windows between monitors and switch focus between opened windows.
Here is good intro: http://thume.ca/howto/2012/11/19/using-slate/ .
My .slate is still pretty poor, I even didn't convert yet to .js format: https://github.com/kozikow/dotfiles/blob/master/.slate .
You can program it in Javascript: https://github.com/jigish/slate/wiki/JavaScript-Configs .


Slate is not really a Tiling window manager. I plan to try some xmonad ports for Mac.
Amethyst ( https://github.com/ianyh/Amethyst  ), Xnomad ( http://onethingwell.org/post/44220275446/xnomad  ) or OsxMonad ( http://onethingwell.org/post/44862454682/osxmonad  ) or ( http://www.haskell.org/haskellwiki/Xmonad/Using_xmonad_on_Apple_OSX ).

Useful system wide shortcuts and settings:
------------------------------------------
* http://guides.macrumors.com/Keyboard_shortcuts 
* When in ANY mac application you can press "cmd+shift+?" to search through all menu items available in that app.
* Some people don't know that you can change any Cocoa application shortcuts by going to Preferences->Keyboard->Keyboard Shortucts->Application Shortcuts.
I recommend to remap "go to next tab/chat/whatever" to same shortcut, since applications tend to have different one.
Cmd+Alt+arrows was the only one that wasn't conflicting and worked in all apps.
* Ctrl+f2 shortcut changes focus to menu bar, so you can navigate it with arrows. For some reason sharted working for me only after I remapped it to different binding.
* Turn full keyboard access on by going to Keyboard->Keyboard Shortcuts->All Controls. Then you would be able to control any mac application prompt using your keyboard.
Space to cycle between options, space to choose highlighted option, enter to choose default option.
* You can usually cycle through availbale items using tab. Some applications implement cycling backwards using shift+tab
* Cmd + Alt + D Hides dock. If you will mostly use slate as I do it's wasted screen space.

Launcher:
---------
I use Alfred: http://www.alfredapp.com/ .
Another alternative is QuickSilver, but I heard Alfred is better.
Options worth mentioning:
* Configure search engines. Ones I most frequently use are Google,
  Gmail, docs search, Jira, Wiki
* Use "1p website" to launch any website and logging through 1password
* "> command" to run command in terminal
* For really frequently visited websites I have a "blank" search engine,
  which serves as bookmark. For example I just type "pulls" to open list of pull
requests
* built in calculator
* Using Alfred workflows (Premium, http://support.alfredapp.com/workflows ) you can do quite a lot. I frequently use it to Control Spotify, Evernote, add remember the milk tasks, kill top processes, google translate, change units, currencies, run build/tests and get growl notification when it completes, lookup time in timezone and open/search through/delete recently downloaded files. You can post to twitter.

Shortcat
--------
http://shortcatapp.com/ .  This application allows you to control all applications that implement accessibility using keyboard. Some use cases according to the website:
* Switching channels in Textual
* Switching chats in Skype
* Clicking links in chat applications
* Changing settings in System Preferences
* Browsing the web in Safari
* Using applications within the iOS Simulator

Chat
----
Any mac standalone application can be controlled with shortcuts.
I use Adium, which allows me to talk with my Facebook and Skype contacts at once and I can control it with keyboard.

Text editor
-----------
I recommend Vim. Configuring Vim is too long topic for this post.
If you want to have pretty well configured Vim out of box I recommend this: https://github.com/square/maximum-awesome . 
Janus ( https://github.com/carlhuda/janus ) is another option, but I think maximum-awesome is better.
Imho the best way to learn Vim is first doing Vimtutor and then reading book Practical Vim by Drew Neil.


Another nice option is to use Emacs with Evil (extensible vi layer - vim emilation) mode. It works very well, there are even some plugins ported.

Terminal
--------
As general tip not related to this guide iTerm is way better than built in Mac terminal.
Instead of using traditional terminal you can use Conque or Vimshell - terminal inside Vim.
It lets you select, navigate and copy terminal output with keyboard, because console output can be treated as vim buffer.
Both Conque and Vimshell feel still immature and have a few minor bugs that may be annoying.
For example opening vim over ssh is buggy in both of them.
Conque felt more mature than Vimshell, but Vimshell on the other hand was actively developed.


Another option is to use eshell - built in emacs shell.
If you install Evil mode you can use navigate output using vim commands.
But it takes a lot of configuration and learning to use it, so I don't recommend it unless you are really determined to find perfect workflow or you are emacs user already.


Two useful terminal commands:
pbcopy coppies it's piped input to clipboard.
vim - openes it's input as a vim window.
For example "ls | vim -". 

Browsing
--------
Chrome with add-on Vimium:
http://lifehacker.com/5925220/make-chrome-less-distracting-with-Vimium-and-these-settings .
It sometimes conflicts with shortcuts in some web applications, like Gmail, but you can either disable vimium on some urls, or use insert mode.
It doesn't work in empty tabs due to chrome security restrictions.
For this reason I recommend using cmd+w for closing tabs and remap select next tab as I said previously.
If you use Firefox, Vimperator have more features than Vimium - for example you can select text using only keyboard.

Gmail
-----
Gmail have it's own excellent set of shortcuts. Just press "?" while in Gmail.

Cheat sheets
------------
I don't like printed cheat sheets.
You can't search through them.
You can't delete items you already remember.
You can't mix up shortcuts from different sources.
You can't add shortcuts you remapped.
I personally maintain evernote note for shortcuts I want to remember in each app.