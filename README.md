# kivy-pingPong_Game [![Build Status](https://secure.travis-ci.org/oncletom/mailto.png?branch=master)](http://travis-ci.org/oncletom/mailto)

> Ping Pong Game App is here
<img src="https://github.com/triyam/kivy-pingPong_Game/blob/main/pong.jpg" width="500" height="400">
<hr>

## But you have to download kivy and subsequent libraries starting with virtual environment which is strongly recommended:
    
    # For windows users
    python -m virtualenv kivy_venv
    kivy_venv\Scripts\activate
    source kivy_venv/Scripts/activate
    
    # For linux users
    python -m virtualenv kivy_venv
    kivy_venv\Scripts\activate
    source kivy_venv/bin/activate
    
## For kivy:

    python -m pip install kivy[master] kivy_examples
    # or
    pip install kivy[master] kivy_examples
    # or 
    pip3 install kivy[master] kivy_examples
    
## For Building it to android, ios, or windows, you must have linux system:

    pip install buildozer
    buildozer init
 
## Make changes in spec file:

    # (str) Title of your application
    title = KvPong

    # (str) Package name
    package.name = kvpong

    # (str) Package domain (needed for android/ios packaging)
    package.domain = org.kvpong
 
## For android:

    buildozer -v android build debug deploy

## For iOS:
    
    brew install autoconf automake libtool pkg-config
    brew link libtool
    sudo easy_install pip
    sudo pip install Cython==0.29.10
    
    git clone git://github.com/kivy/kivy-ios
    cd kivy-ios
    ./toolchain.py build python3 kivy
    
    cd /Applications/Python\ 3.7/
    ./Install\ Certificates.command
    
    ./toolchain.py create <title> <app_directory>
    
## For Windows:
    
    pip install pyinstaller
    pyinstaller main.py -w
    
## For macOS:

    pyinstaller main.py -w --onefile
<hr>
<h5>If still any problem exist you can mail to me at <a href="mailto=triyambakam2@gmail.com">triyambakam2@gmail.com</a></h5>
<h6>Thanks For Visiting</h6>


    
    
    
