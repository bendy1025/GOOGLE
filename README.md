# GOOGLE
Help with installing the Chrome web browser


# Download Google Chrome

You can download the latest version of Google Chrome from their official website. For this, you can use the command-line with wget:

```
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb

```
This will download the .deb package of Google Chrome for 64-bit systems, which is standard for most modern systems. If you have a different architecture, you'll need to get the appropriate package from Google Chrome's download page.

# Install Google Chrome

To install the package you've just downloaded, run the following command:

```
sudo dpkg -i google-chrome-stable_current_amd64.deb

```
During the installation process, it's possible that you might encounter some dependency errors. If this happens, you can fix it and complete the installation by running:

```
 sudo apt --fix-broken install

```

# Launch Google Chrome

Once installed, you can launch Google Chrome from the application menu or from the terminal using:

```
google-chrome-stable

```

# Optional: 
## Create a Desktop Shortcut (if it doesn't automatically exist)

If, for some reason, a desktop shortcut isn't created, you can manually create one:

Navigate to the applications directory:

```
cd /usr/share/applications/

```
Copy the google-chrome.desktop file to your desktop:

```
cp google-chrome.desktop ~/Desktop/

```
Now, you'll have a shortcut on your desktop that you can double-click to start Google Chrome.

That's it!


IZZY


