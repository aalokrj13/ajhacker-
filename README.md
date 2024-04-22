# ajhacker-
this is my first  git repository 
Skip to content
htr-tech
/
zphisher

Type / to search

Code
Issues
105
Pull requests
16
Actions
Security
Insights
Owner avatar
zphisher
Public
htr-tech/zphisher
Go to file
t
Add file
Folders and files
Name		
Latest commit
htr-tech
htr-tech
Fix Order
615d9f8
 · 
last year
History
.github
Rename SUMS to CHECKSUMS
2 years ago
.sites
Updated Page: twitch
2 years ago
scripts
Revert "Revert "Update to 2.3.0""
2 years ago
Dockerfile
Revert "Revert "Update to 2.3.0""
2 years ago
LICENSE
Create LICENSE
5 years ago
README.md
feat: remove ngrok
last year
make-deb.sh
Update to 2.3.5
2 years ago
run-docker.sh
Revert "Revert "Update to 2.3.0""
2 years ago
zphisher.sh
Fix Order
last year
Repository files navigation
README
GPL-3.0 license


    

    

A beginners friendly, Automated phishing tool with 30+ templates.

Disclaimer

Any actions and or activities related to Zphisher is solely your responsibility. The misuse of this toolkit can result in criminal charges brought against the persons in question. The contributors will not be held responsible in the event any criminal charges be brought against any individuals misusing this toolkit to break the law.

This toolkit contains materials that can be potentially damaging or dangerous for social media. Refer to the laws in your province/country before accessing, using,or in any other way utilizing this in a wrong way.

This Tool is made for educational purposes only. Do not attempt to violate the law with anything contained here. If this is your intention, then Get the hell out of here!

It only demonstrates "how phishing works". You shall not misuse the information to gain unauthorized access to someones social media. However you may try out this at your own risk.

Features
Latest and updated login pages.
Beginners friendly
Multiple tunneling options
Localhost
Cloudflared
LocalXpose
Mask URL support
Docker support
Installation
Just, Clone this repository -

git clone --depth=1 https://github.com/htr-tech/zphisher.git
Now go to cloned directory and run zphisher.sh -

$ cd zphisher
$ bash zphisher.sh
On first launch, It'll install the dependencies and that's it. Zphisher is installed.

Installation (Termux)
You can easily install zphisher in Termux by using tur-repo

$ pkg install tur-repo
$ pkg install zphisher
$ zphisher
A Note :
Termux discourages hacking .. So never discuss anything related to zphisher in any of the termux discussion groups. For more check : wiki



Installation via ".deb" file
Download .deb files from the Latest Release

If you are using termux then download the *_termux.deb

Install the .deb file by executing

apt install <your path to deb file>
Or

$ dpkg -i <your path to deb file>
$ apt install -f
Run on Docker
Docker Image Mirror:

DockerHub :
docker pull htrtech/zphisher
GHCR :
docker pull ghcr.io/htr-tech/zphisher:latest
By using the wrapper script run-docker.sh

$ curl -LO https://raw.githubusercontent.com/htr-tech/zphisher/master/run-docker.sh
$ bash run-docker.sh
Temporary Container

docker run --rm -ti htrtech/zphisher
Remember to mount the auth directory.
Dependencies
Tested on
:: Workflow ::


Find Me on:
 

Thanks to all contributors:

1RaY-1	
Aditya Shakya	
Ali Milani	
AmnesiA	
KasRoudra	
Moises Tapia

Mr.Derek	
Mustakim Ahmed	
sepp0	
TripleHat	
Yisus7u7
About
An automated phishing tool with 30+ templates. This Tool is made for educational purpose only ! Author will not be responsible for any misuse of this toolkit !

Topics
phishing phishing-attacks phisher phishing-pages htr-tech zphisher
Resources
 Readme
License
 GPL-3.0 license
 Activity
Stars
 10.3k stars
Watchers
 745 watching
Forks
 3.3k forks
Report repository
Releases 10
Zphisher Release 2.3.5
Latest
on Jan 3, 2023
+ 9 releases
Contributors
15
@htr-tech
@E343IO
@adi1090x
@MoisesTapia
@1RaY-1
@Yisus7u7
@BDhackers009
@seppzer0
@AliMilani
@KasRoudra
@russorat
@fossabot
@aryan9868
@Meht-evaS
@TripleHat
Deployments
50
 github-pages 4 years ago
+ 49 deployments
Languages
HTML
90.1%
 
CSS
6.6%
 
PHP
2.7%
 
Other
0.6%
Footer
© 2024 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact
Manage cookies
Do not share my personal information
