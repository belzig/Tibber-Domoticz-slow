Floppy999 archived the original repo. So this fork was necessary, in order to fix the code in order to prevent the plugin from exessive polling the Tibber Server.

Important, you must Allow new devices, in Domoticz, Setup-Settings-System-Hardware/Devices.

Create a folder with a name that you like in "domoticz/plugins"  
Put plugin.py, tibber.zip, requirements.txt in that folder  

or

In domoticz/plugins run command "sudo git clone  https://github.com/Shakelton52/Tibber-Domoticz-slow.git"

-------------------

Run "sudo pip3 install -r requirements.txt" to install all packages that this plugin needs  
Restart Domoticz  
Add Tibber from Hardware  
Input your Token and HomeID, get it by log in to this page https://developer.tibber.com/explorer  
Load personal token and paste below code click PLAY
```
{
  viewer {
    homes {
      id
    }
  }
}
```

![](./tibber.png "Photo")


Support me with a coffee https://www.buymeacoffee.com/flopp999
