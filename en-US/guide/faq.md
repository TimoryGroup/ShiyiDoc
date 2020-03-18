# Frequently Ask Questions (FAQ)

### How to apply the Whitelist?
- [[Whitelist Applcation]](/en-US/join/whitelist.md)

### What should I do after join server?
- This page is wip
- [Guidance](/en-US/guide/playerGuide.md)

### What is the server address? Which version should I use?
- See: [[Server Info]](/en-US/guide/serverInfo.md)

### Do I need to reapply for the whitelist after I changed my ID ?
- Minecraft accounts use a series of characters called UUIDs to represent users.
- The UUID of each user is different and cannot be modified after registration.
- Modifying the game ID does not modify the UUID, so the whitelist does not expire.
    - You can see [[here]](https://namemc.com/) to lookup your UUID.

### Unable to join server
- #### ``Cannot resolve hostname``
     - Check the address you entered
     - Flush your dns
- #### ``Can't connect to server``
    - Check the group announcement to see if server is maintaining
        - YES：
            - Please wait patiently for maintenance
        - NO：
            - Please contact the administrator
- ####  ``failed to login: invalid session``
    - Reboot your client
- ####  ``您尚未申请白名单``
    - Please apply whitelist first in here: [[Whitelist Applcations]](/en-US/join/whitelist.md)
- ####  ``Outdated Server `` or  ``Outdated Client`` 
    - See: [[Server Info]](/en-US/guide/serverInfo.md)
    
### Will maliciously damage in the server?
- We have CoreProtect plugin, which can log (also rollback) the actions of each player.
- You can use ``/ co i`` to open the lookup tools,
    - left-click the block to lookup the placement record.
    - right-click the container to view the item operation record.
- If your property have been damaged, contact admin.

### When will the new version updated?
- Upgraded version may bring unexpected problems.
- in order to be responsible to everyone, we will not update the latest version immediately.
    - First, we need to wait for the release of the new stable server (Spigot / Paper). 
 when we confirmed that there is no problem, we will update the version.
    - Some plugins may not be compatible with the new version, 
    then we will support the entry of the new version client
    (but will not include the new version of the game content)
    - If the new version is not compatible with the current version, 
    we will notify within the group and consider deleting files as appropriate.
    - Under normal circumstances, server will be updated about 1-3 months after the new version is released.

### Does the server delete world?
- World not be deleted unless:
    - New version is not compatible with old version
    - World badly damaged
    - Other special circumstances 
- After change to new world, download will available for the old world.     
        
### How to check the online player？
- Lookup in Telegram **is not support yet**, you need to use the Tencent QQ.
- Send command: ``:list`` to bot（QQ: 26897**649）in private chat on QQ.
- If bot has not responded for a long time, contact admin.


### What is the server hardware？
- Hardware：
    - GameServer:
        - CPU: intel i7-6700 @3.7G
        - RAM: DDR3 28G(3*8+4) 
        - Disk:
            - Samsung 860EVO 480G SSD(System Runtime & Minecraft Runtime )
            - Samsung 850EVO 120G SSD(Database Runtime)
            - WDC 2T HDD (Backup Storage) 
        - Network:
            - ChinaTelecom 200Mbps
            - AlibabaCloud BGP router, Guangzhou, China.

### Does the server have API?
- doc: [[Api Doc]](/en-US/dev/api.md)

