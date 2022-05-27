# bye-liking-baidu-websites

Update 27 May 2022 EST 0:30 AM

Fix `can't access twitter`:

1.[Refresh or execute computer terminal](https://gist.github.com/SofijaErkin/29003a942396276ba5719ec3a2e44f1b#3refresh-or-execute-computer-terminal)

2.Change local DNS servers TO Google DNS `8.8.8.8` and `8.8.4.4`.

If you are using macOS, touch down `apple logo` -> `System Preferences` ->

`Network` -> `Advanced` -> `DNS` -> `DNS Servers` -> push down `IPv4or IPv6 address`

-> edit `0.0.0.0` to `8.8.8.8` -> make sure push button `ok` -> Again add

`DNS Servers address` with `8.8.4.4`.

(Notices: Does not include reference books)

I will introduce the more details of this project in the future, if I have time.

------------------------------Personal Statement-----------------------

First of all, the most important thing is:

I don't dislike liking Baidu companies,

but I dislike some of their products.

Also, I dislike some of their business models or patterns.

eg:I don't dislike that product Baidu Tieba. Or, I don't hate

Baidu's signboard either.

At least, they gives a personal opportunity.

------------------------------Personal Statement--------------------

So, So, So

（Only on the computer. Phone or tablet won’t work）

Are you tired of Baidu search？

Are you tired of Baidu ads？

Are you tired of Baidu Cloud Disk？

## Now

It's time to say bye to liking Baidu sites.

### Please follow the instructions below

You know, I need to fundamentally block liking Baidu websites.

That means that after blocking liking Baidu websites, I cannot access liking

baidu websites from applications, websites, or even computer terminals. Of

course, I know it's very cool.

My idea is to modify the hosts file

(the hosts file is in the etc directory of macOS)

Please shine on the cat painting the mimicry,

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

In short, edit hosts:

"cd .. && cd .. && cd etc && sudo vi hosts"

#### 3.Refresh or execute computer terminal

Refresh or execute computer terminal，that means Clear/flush DNS cache.

DNS: Domain name server.

Just use the command:

In macOS:

1.macOS Sierra, macOS X El Capitan, macOS X Mavericks, 

macOS X Mountain Lion, macOS X Lion

sudo killall -HUP mDNSResponder

2.macOS X Yosemite

sudo discoveryutil udnsflushcaches

3.macOS X Snow Leopard

sudo dscacheutil -flushcache

4.macOS X Leopard and below

sudo lookupd -flushcache

OR, no matter what your macOS was, just use:

sudo dscacheutil -flushcache

In windows:

1.push button "Windows+R";

2.RUN window:flush-DNS-2;

3.input "CMD";

4."Enter"key;

5.input "ipconfig/flushdns " + "Enter" key;

In Linux: sudo /etc/init.d/networking restart.

#### 4.Exit the computer terminal and restart the computer

#### 5.disable all the blank

just use command to remove that host:

"sudo rm -r dir"

or

edit that host :

add '#' before "127.0.0.1"

Finally, ":wq" + Enter key and Clear/flush DNS cache.

OK，that's All.

Over, thanks!
