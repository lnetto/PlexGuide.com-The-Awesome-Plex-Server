# PlexGuide.com - Developer Version NGINX
 
<p align="center">
  <img src="https://github.com/Admin9705/PlexGuide.com-The-Awesome-Plex-Server/blob/Version-5/scripts/plexguide.PNG" alt="PlexGuide.com Logo"/>
</p>

**D. Install Instructions:**

*Install GIT*
```sh
sudo apt-get wget
sudo apt-get unzip
```

*Install PlexGuide*
```sh
sudo rm -r /opt/plexg* 2>/dev/nu*
sudo wget https://github.com/Admin9705/PlexGuide.com-The-Awesome-Plex-Server/archive/Legacy-V4.zip -P /tmp
sudo unzip /tmp/Legacy-V4.zip -d /opt/
sudo mv /opt/PlexG* /opt/plexguide
sudo bash /opt/plexg*/sc*/ins*
sudo rm -r /tmp/Legacy-V4.zip
```

*Execute PlexGuide AnyTime Futurewise*
```sh
plexguide
```
