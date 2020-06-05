# iCopy
Copy GoogleDrive Resources via [Telegram](http://telegram.org) BOT

## Install  
1.Python 3.6+ is Required  
2.Pre-install screen
3.Pre-install and Configured [gclone](https://github.com/donwa/gclone) is Reqired  
  For Linux directly use this command  
  `bash <(wget -qO- https://git.io/gclone.sh)`  
4.`pip install python-telegram-bot`  
5.`git clone https://github.com/fxxkrlab/iCopy.git && cd iCopy`  
6.`cp settings.py.example settings.py`  
7.Edit settings.py   

* TOKEN : Bot API Token generated by BotFather  
* ENABLED_USERS : Your telegram user id. Only enabled users can use this bot.  
* Remote : Your gclone config name.like "gc"
* Pre_Dst_id : Pre-Assigned Google Drive Destination Folder ID for quick mode

#### Start iCopy BOT :   
``screen -dmS iCopy `which python3` -u iCopy.py``  

#### 本项目意在方便群友自定义转存机器人以及快捷命令  
#### 若有网上的朋友不明白的欢迎加TG群 [Google Drive 资源互通](https://t.me/sharegdrive)  