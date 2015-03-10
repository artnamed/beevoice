# beevoice

if you find something about:<br>
    "voice chat lan"<br>
    "application for voice exchanges in lan network"<br>
    "lightweight voice chat / voip"<br>
    "speech in local network"<br>
    "lan voice chat software"<br>
    "windows voice offline chat"<br>
    "talking with players in local network"<br>
    "automatic voice chat"<br>
    "offline voice chat without gui for gaming"<br>

then this utility can be exactly what you need

Description.
The number of voice chats is very much. Many companies writing application with many features and possibilities. But main problem of exchange programs of voice is parameters tuning of all voice chat procedures.
That version of voice chat tuning for my environment for gaming with my friends.
I'll try list my points of view:
* I have badly internet connection, some times i call to provider and spend pretty time by swearing );
* I want to play, not to chating in boring chat window, i don't want chat window totaly;
* I know what my lan network is only my community, i don't want to registering, adding participants and doing other administrative actions, no administrative totaly. If somebody in my local network who i don't want see, this means something wrong in my local network. If somebody want to join, i don't want to stop game and add him, he just run application and talking;
* I want to give cpu and memory to my game, not to voice chat application. I leave idea of encryption and buffering;

After that I have main principles:
* no server (internet access), that feature need for offline
* low cpu and memory harvesting (more tuning for cpu and memory then net traffic, because lan network in this case)
* no gui (administrating off)
* no secure (for tuning cpu and memory)

How it is working?<br>
Is very simple!<br>
After starting application, console will be opened and all procedures will working automatically.<br>
Network neighbour processing: send hello to broadcast and to any NET VIEW list of computer names in network. NET VIEW is needed, because broadcasts not sending through WiFi connections. Receive hello from other running application. That's all. Any will know about any.<br>
Emitter voice: more simpler. Reading sound data from microphone and send to all friends.<br>
Receiver voice: play every other voice received from network. Yeeh<br>

All this procedure behaviours optimized and tuned for described description.

Archive of build here https://github.com/artnamed/beevoice/raw/master/backup_build/beevoice_v1.0_win32_b0.zip
md5: 2507173acb59b1f2f33fd57fcf9f350c
