# Overbyrns' Plugins for unRAID v5

## Details

This is my collection of plugins for UnRAID;


* **Air Video**: Stream videos in almost any format to your iPhone, iPad and iPod touch. You don't need to copy your videos to the device just to watch them.  If the videos in your collection are not in format supported by iPhone or iPad, Air Video will convert them on fly. You don't need to wait until the entire video is converted. You can start watching it almost immediately

* **Beets**: The purpose of beets is to get your music collection right once and for all. It catalogs your collection, automatically improving its metadata as it goes using the MusicBrainz database. (It also downloads cover art for albums it imports.) Then it provides a bouquet of tools for manipulating and accessing your music.

* **BTSync**: Synchronizes files using a peer-to-peer (P2P) protocol. This protocol is very effective for transferring large files across multiple devices, and is very similar to the powerful protocol used by applications like µTorrent and BitTorrent. The data is transferred in pieces from each of the syncing devices, and BitTorrent Sync chooses the optimal algorithm to make sure you have a maximum download and upload speed during the process.

* **DenyHosts**: Analyzes the sshd server log messages to determine what hosts are attempting to hack into your system. It also determines what user accounts are being targeted. It keeps track of the frequency of attempts from each host. Additionally, upon discovering a repeated attack host, the /etc/hosts.deny file is updated to prevent future break-in attempts from that host. 

* **Dropbox**: Free service that lets you bring all your photos, docs, and videos anywhere. This means that any file you save to your Dropbox will automatically save to all your computers, phones and the Dropbox website.  This plug-in makes it possible to use your UnRAID server as a Dropbox location.

* **NZBGet**: A cross-platform binary newsgrabber for nzb files, written in C++. It supports client/server mode, automatic par-check/-repair and a web-interface. NZBGet requires low system resources making it ideal for running alongside UnRAID.

* **OpenSSH**: Provides encrypted communication sessions over a computer network using the SSH protocol.  SSH is typically used to log into a remote machine and execute commands, but it also supports tunneling, forwarding TCP ports and it can transfer files using the associated SSH file transfer (SFTP) or secure copy (SCP) protocols.

## Download Links
Use the following direct links to download each plugin:

Air Video - (https://github.com/overbyrn/UnRAID/raw/master/airvideo_overbyrn.plg)<br>
Beets - (https://github.com/overbyrn/UnRAID/raw/master/beets_overbyrn.plg)<br>
BTSync - (https://github.com/overbyrn/UnRAID/raw/master/btsync_overbyrn.plg)<br>
DenyHosts - (https://github.com/overbyrn/UnRAID/raw/master/denyhosts_overbyrn.plg)<br>
Dropbox - (https://github.com/overbyrn/UnRAID/raw/master/dropbox_overbyrn.plg)<br>
NZBGet - (https://github.com/overbyrn/UnRAID/raw/master/nzbget_overbyrn.plg)<br>
OpenSSH - (https://github.com/overbyrn/UnRAID/raw/master/openssh_overbyrn.plg)<br>


## Installation
<p>
1. Download the plugin eg. (https://github.com/overbyrn/UnRAID/raw/master/nzbget_overbyrn.plg)<br>
2. Copy the plug-in to /boot/config/plugins on your flash drive<br>
3. Reboot your UnRAID server or alternatively if you are currently using your server eg. it is working on something else, parity check, preclearing etc, you can install it from command line:

<pre><code>installplg /boot/config/plugins/nzbget_overbyrn.plg</pre></code>
    
4. Go to UnRAID WebGui -> Settings -> NZBGet and configure your initial settings
</p>

## Plug-in Updates
From time to time, changes may be required to the plug-in.  eg. bug fixes, enhancements.  With the exception of Beets, the plug-in is designed to check for updates to itself upon entering the plug-in settings page. If a later version is found, you will be presented with an option to update. The update process will stop the application (if running), perform the update and restart the application.  A backup copy of the plug-in is saved to /boot/config/plugins/<plugin_name> as <plugin_name>_overbyrn.plg.sav.

## Support
Please provide feedback to any problems encountered or to request enhancements or missing features that you would like to see added.  


