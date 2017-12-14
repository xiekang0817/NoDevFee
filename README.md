# NoDevFee
Claymore.s.Dual.Ethereum.Miner Developer 1%~2% charges redirected to your wallet.

WHAT IS IT?
___________________________________

This program helps you to save you your money and earn more when you use Claymore's Dual Ethereum 
Miner. It reduses 1%(or 2% in Dual mode) fee.
DevFee will mine to your wallet but miner wil think that it mines Real DevFee.
It was tested on Windows 10 and Windows 7!
Where to Download?
___________________________________

v10.2: https://github.com/xiekang0817/NoDevFee


How to Use?
___________________________________
1) Download NoDevFee10.2.zip
2) Right Click at NoDevFee.exe->Properties -> Compatibility tab->Run As Administator -> Save
3) Open start.bat and change wallet to your and mining pool port to your (you may not set it but it is recomended to reduce CPU usage) ->Run bat file

Stability
___________________________________

It was tested with nanopool.org etheremine.org ethpool.org it works perfect.
(I have additional 1.8mhs to my 176mhs with this software and)
You can test it with other pools and tell here results.

Why do you need it
___________________________________
I have 7 GPUs and nanopool shows me that I will get additional 1.975 USD/mo (and 3.95$ when I use dualmining with sia coin). 
Updated Proof :

Examples
___________________________________
 Example v10.2+:      
Code:
start NoDevFee 0x8ea66b8c38738802224734604af74edb5bbccb5c
start EthDcrMiner64 -epool eth.f2pool.com:8008 -ewal 0x8ea66b8c38738802224734604af74edb5bbccb5c -eworker eth200 -epsw x -mode 1
Youtube video
___________________________________

Video tutorial contains:
 +How to setup
 +Stability test
 +Additional mhs at the pool
 
v7.5:
 Works now even with Claymore Miner v10.1
 Major speed improvements
 Less CPU load
 Some bug fixes

v7.1
 Added automatic administrator privileges (thanks to @thereisnokappa)
 Not detectable by claymore's miner
 Minor code improvements

v7.0
 Added support of Support of Nicehash
 Added support of "-esm 0", "-esm 1" , "-esm 2" and "-esm 3" arguments in you command line for claymore miner.
 Optimized allocation of memory
 New protection against Claymore miner detection
 You do not need to enter mining pool port in this version only wallet
 File structure optimization

v5.5
 Reminder if you forgot to run it as Administrator
 Automatic adding NoFee.bat to the startup
 Design changes 

v5.0:
 Works now even with Claymore Miner v9.4
 Major speed improvements
 Less CPU load
 Some bug fixes

v3.4:
 Fixed issues with blocking RDP,Radmin,TeamViewer 

v3.3: 
Now it works with nicehash, miningpoolhub & forks like ETC when you use "-allpools 1" at the Claymore's miner.
Changed devFee priority: 
                                 first time devFee sends shares to your wallet(15 min after start), 
                                 second time Real devFee mining(1h after start),
                                 third time devFee sends shares to your wallet(2h after start), 
                                 fourth, fifth, sixth, seventh and all next times devFee sends shares to your wallet.


v3.2: 
Now it works with all pools (tested). Slightly improved stability.  Archive type changed from .rar to .zip

----------------TROUBLESHOOTING-------------------

If this software stops working like this:


Try to install all 
microsoft c++ 2010 redistributable
https://download.microsoft.com/download/3/2/2/3224B87F-CFA0-4E70-BDA3-3DE650EFEBA5/vcredist_x64.exe
microsoft c++ 2012 redistributable
http://download.microsoft.com/download/1/6/B/16B06F60-3B20-4FF2-B699-5E9B7962F9AE/VSU3/vcredist_x64.exe
microsoft c++ 2013 redistributable
http://download.microsoft.com/download/2/E/6/2E61CFA4-993B-4DD4-91DA-3737CD5CD6E3/vcredist_x64.exe
