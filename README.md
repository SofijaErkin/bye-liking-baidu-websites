# bye-liking-baidu-websites
（Only on the computer. Phone or tablet won’t work）

Are you tired of Baidu search？

Are you tired of Baidu ads？

Are you tired of Baidu Cloud Disk？
## Now 
It's time to say bye to Baidu sites.
### Please follow the instructions below
You know, I need to fundamentally block liking Baidu websites. 

That means that after blocking liking Baidu websites, I cannot access liking 

baidu websites from applications, websites, or even computer terminals.


Of course, I know it's very cool.

My idea is to modify the hosts file 

(the hosts file is in the etc directory of macOS)

Plesse shine on the cat painting the mimicry, 

if you are windows or Linux User.

#### 0.Please download hosts file
hosts file was on the directory bye-liking-baidu-websites/ 

of my github project, my project was bye-liking-baidu-websites.


#### 1.Find and open the computer terminal
In macOS：Terminal, iTerm2, or others;

In windows: Windows Terminal, ConEmu, Cmder, ConsoleZ;

In Linux: Lilyterm, Konsole, XFCE4(xfce4-terminal), Terra Terminal Emulator, 

terminator, tmux, LXTerminal, xterm, urxvt, suckless st, guake, GNOME, 

Yakuake or Others.


#### 2.Please copy the downloaded file to the /etc directory
Please use commands. like "cp -r dir1 dir2".

cp -r dir1 dir2: copy dir1 to dir2; create dir2 if it doesn't exist.

the downloaded file: hosts, 

the /etc directory:

In macOS：~/private/etc;

In windows:C:\Windows\System32\drivers\etc.

eg: my downloaded file hosts was on /Users/my123mac/Downloads/,

my /etc directory was on /etc,

so, my dir1 was "/Users/my123mac/Downloads/hosts",

and my dir2 was "/etc/hosts".

then, my command "cp -r dir1 dir2" was

"cp -r /Users/my123mac/Downloads/hosts /etc/hosts".

OR

"sudo cp -r /Users/my123mac/Downloads/hosts /etc/hosts".

#### 3.Refresh or execute computer terminal
Refresh or execute computer terminal，that means Clear/flush DNS cache.

DNS: Domain name server.

Just use the command:

In macOS:

1.Mac OS Sierra, Mac OS X El Capitan, Mac OS X Mavericks, Mac OS X Mountain Lion, Mac OS X Lion
sudo killall -HUP mDNSResponder
2.Mac OS X Yosemite
sudo discoveryutil udnsflushcaches
3.Mac OS X Snow Leopard
sudo dscacheutil -flushcache
4.Mac OS X Leopard and below
sudo lookupd -flushcache

In windows: 

1.push button "Windows+R";

2.RUN windos:flush-DNS-2; 

3.input "CMD"; 

4."Enter"key;

5.input "ipconfig/flushdns " + "Enter" key;

In Linux: sudo /etc/init.d/networking restart.

#### 4.Exit the computer terminal and restart the computer


OK，that's ALl.

Over, thanks!
