For Windows 10 & 8

Press the Windows key.

Type Notepad in the search field.

In the search results, right-click Notepad and select Run as administrator.

From Notepad, open the following file: c:\Windows\System32\Drivers\etc\hosts

Make the necessary changes to the file.

Click File > Save to save your changes.


#############################################################################

For Linux

Open a terminal window.

Open the hosts file in a text editor (you can use any text editor) by typing the following line:

sudo nano /etc/hosts

#############################################################################

For Mac OS X 10.6 through 10.12

Open Applications > Utilities > Terminal.

Open the hosts file by typing the following line in the terminal window:

sudo nano /private/etc/hosts

Type your domain user password when prompted.

Edit the hosts file.The file contains some comments (lines starting with the # symbol), and some default hostname mappings (for example, 127.0.0.1 – local host). Add your new mappings after the default mappings.

Save the hosts file by pressing Control+x and answering y.

Make your changes take effect by flushing the DNS cache with the following command:

dscacheutil -flushcache
