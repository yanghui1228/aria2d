# aria2d
    aria2d 是基于aria2的自动下载多个torrent文件的命令行工具。
    
    aria2d is a CLI shell script to batch trigger the torrent downloads in one shot via aria2c.
    This utility is only tested on MacOS Mojave so it may not work in the other platform.
    it will update your bt-trackers from server if your conf file is in ~/.aria2/aria2.conf
  
## Dependencies:
    This project is dependent on packages: `aria2c wget`.
    Use 'brew list' to check your installed packages.
    Use 'brew install aria2c wget' to install
    
## Usage:
    Copy 'aria2d' to your Mac's /usr/local⁩/⁨bin/ folder⁩ and then just trigger command - aria2d.
    Please note it will trash your torrent files, so the same task won't trigger again.
    For stopped downloads to resume, restore your torrent from the trash can and run it again.
