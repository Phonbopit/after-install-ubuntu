
## My top things to do after Installing Ubuntu

**1. Update & Upgrade**

    sudo apt-get update
    sudo apt-get upgrade
    
**[2. Install Ubuntu Restricted Extras](https://apps.ubuntu.com/cat/applications/ubuntu-restricted-extras/) **

    sudo apt-get install ubuntu-restricted-extras
    
**[3. Install Numix GTK Theme & Circle](http://numixproject.org/public/)**

    sudo add-apt-repository ppa:numix/ppa
    sudo apt-get update
    sudo apt-get install numix-gtk-theme
    sudo apt-get install numix-icon-theme-circle
    
**[4. Install Chrome Browser](https://www.google.com/intl/en/chrome/browser/)**

**5. Upgrade Graphic Drivers**

- [AMD/Intel Hybrid](http://ubuntuforums.org/showthread.php?t=1930450)


**[6. Create Launcher Icon](http://www.howopensource.com/2012/10/create-application-launcher-add-icon-to-unity-ubuntu-12-10/)**

    sudo apt-get install --no-install-recommends gnome-panel
    sudo gnome-desktop-item-edit /path/to/store/icon --create-new

**[7. Install Java](http://www.webupd8.org/2012/01/install-oracle-java-jdk-7-in-ubuntu-via.html)**

    sudo add-apt-repository ppa:webupd8team/java
    sudo apt-get update
    sudo apt-get install oracle-java7-installer
    #Check java version
    java -version
    javac -version
    
**[8. Install Git](http://git-scm.com/)**

    sudo add-apt-repository ppa:git-core/ppa
    sudo apt-get update
    sudo apt-get install git
    
**9. Setup Git**

    git config --global user.name "myname"
    git config --global user.email "my@email.com"
    #check git settings
    git config --list

    
**[10. Setup SSH & Generating SSH Keys](https://help.github.com/articles/generating-ssh-keys)**

    sudo apt-get install ssh
    cd ~/.ssh
    ssh-keygen -t rsa -C "my@email"
    sudo apt-get install xclip
    xclip -sel clip < ~/.ssh/id_rsa.pub
    
**[11. Install Ubuntu Tweak](http://ubuntu-tweak.com/)**

    sudo add-apt-repository ppa:tualatrix/ppa
    sudo apt-get update
    sudo apt-get install ubuntu-tweak

**[12. Install NodeJS](https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager)**

    sudo apt-get install python-software-properties python g++ make
    sudo add-apt-repository ppa:chris-lea/node.js
    sudo apt-get update
    sudo apt-get install nodejs

**[13. Install Ruby & Rails](https://rvm.io/)**

    sudo apt-get install curl
    curl -L https://get.rvm.io | bash -s stable
    source ~/.rvm/scripts/rvm
    rvm requirements
    rvm install ruby
    rvm use ruby --default
    gem install rails
    

**[14. Install Sublime Text2](http://www.webupd8.org/2012/06/sublime-text-20-stable-released-ppa.html)**

    sudo add-apt-repository ppa:webupd8team/sublime-text-2
    sudo apt-get update
    sudo apt-get install sublime-text
    
**[15. Sublime Favorite Plugins](https://sublime.wbond.net/)**

- [Emmet](https://sublime.wbond.net/packages/Emmet)
- [SublimeLinter](https://sublime.wbond.net/packages/SublimeLinter)
- [SublimeCodeIntel](https://sublime.wbond.net/packages/SublimeCodeIntel)
- [BracketHighlighter](https://sublime.wbond.net/packages/BracketHighlighter)
- [MarkdownEditing](https://sublime.wbond.net/packages/MarkdownEditing)
- [AngularJS]()
- [ColorPicker](https://sublime.wbond.net/packages/ColorPicker)
- [Pretty JSON](https://sublime.wbond.net/packages/Pretty%20JSON)
- [Tag](https://sublime.wbond.net/packages/Tag)
    
**15. Install Eclipse, ADT Bundle & IDEA**

- [Eclipse](http://www.eclipse.org/downloads/)
- [ADT Bundle](http://developer.android.com/sdk/index.html)
- [Android Studio](http://developer.android.com/sdk/installing/studio.html)
- [IDEA](http://www.jetbrains.com/idea/download/index.html)
- Ubuntu 12.04 64-Bit  `sudo apt-get install ia32-libs`

**[16. Install Genymotion](https://cloud.genymotion.com/page/launchpad/download/)**

    cd path/to/genymotion
    chmod +x genymotion-2.0.3_x64.bin
    ./genymotion-2.0.3_x64.bin
    

**99. Install more programs**

    sudo apt-get install vlc
    sudo apt-get install gimp
    sudo apt-get install inkscape
    

    





