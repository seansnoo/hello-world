{\rtf1\ansi\ansicpg1252\cocoartf2639
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;\f1\fnil\fcharset0 HelveticaNeue;\f2\fnil\fcharset129 AppleSDGothicNeo-Regular;
}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Cyer Raider CTF 1\
## First Flag\
* welcome~padawan\
* located in /home/airmanjoe/readme\
	* Just used cat readme\
\
## Second Flag\
* 
\f1\fs26 nananananananana+batman\
* located in /home/airmanjoe/hidden/.cantseeme\
	* Found using ls -lah\
	* Used cat .cantseeme\
\
## Third Flag\
* Low/orbig\
* located in /home/airmanjoe/\'91spaces in this filename\'92\
	* Used cat \'91spaces then tabbed to auto complete filename.\
\
## Fourth Flag \
* calamity-zebra\
* located in /home/airmanjoe/execute_me\
	* used ls -lah, and saw that file was an executable.\
	* Ran ./execute_me\
\
## Fifth Flag\
* cr18\{4468282076f753640f3574392c730758\}\
* located in /home/airmanjoe/.hidden/.hideme\
	* Found the folder using ls -lah in /home/airmanjoe\
	* Then found inside the .hidden folder using ls -lah again.\
	* Opened file with cat .hideme\
\
## Sixth Flag\
* Bravo-corgi echo-heeler\
* located in /home/airmanjoe/alike\
	* I used diff bravo-corgi echo-heeler\
	* Could also use sha256sum *\
\
## Seventh Flag\
* honest$cap\
* located in /home/airmanjoe/lost/maybeinhere15/file9\
	* while located within the /lost/ directory I used ls -lah maybeinhere## | grep \'91503\'92 on every directory until I found the desired file.\
\
## Bob\'92s Flag\
* butter+chicken\
* Located in /home/airmanbob/bobs.secret\
	* Used su with the example setUID code to change users to airmanbob\
	* cd in /home/airmanbob\
	* cat bobs.secret\
\
## Charles\'92 Flag\
* naturally$better\
* Located in /home/airmancharles/Charles.secret\
	* Used ls -lah and saw that the owner was 1003\
	* Changed user to root with the setUID script.\
	* As root used cat /etc/shadow and cat /etc/group saw that no user 1003 existed.\
	* As root created a new user with sudo adduser. I created the user\'92s name as airmancharles but this was not necessary.\
\
## Ubuntu\'92s Flag\
``` sneaky, I like it.  Unfortunately your flags are in another castle...\
\pard\pardeftab560\slleading20\pardirnatural\partightenfactor0
\cf0 \
            \uc0\u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608             \
        \uc0\u9608 \u9608 \u9608 \u9608           \u9608 \u9608 \u9608 \u9608         \
      \uc0\u9608 \u9608       
\f2 \'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6
\f1       \uc0\u9608 \u9608       \
    \uc0\u9608 \u9608       
\f2 \'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6
\f1       \uc0\u9608 \u9608     \
    \uc0\u9608 \u9608       
\f2 \'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6
\f1         \uc0\u9608 \u9608   \
  \uc0\u9608 \u9608 
\f2 \'a2\'c6\'a2\'c6
\f1       
\f2 \'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6
\f1       
\f2 \'a2\'c6\'a2\'c6
\f1 \uc0\u9608 \u9608   \
  \uc0\u9608 \u9608 
\f2 \'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6
\f1       
\f2 \'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6
\f1         
\f2 \'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6
\f1 \uc0\u9608 \u9608 \
  \uc0\u9608 \u9608 
\f2 \'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6
\f1                     
\f2 \'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6
\f1 \uc0\u9608 \u9608 \
  \uc0\u9608 \u9608 
\f2 \'a2\'c6\'a2\'c6
\f1       \uc0\u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608         
\f2 \'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6
\f1 \uc0\u9608 \u9608 \
  \uc0\u9608 \u9608     \u9608 \u9608 \u9608 \u9608 \u9608 \u9608     \u9608 \u9608 \u9608 \u9608 \u9608 \u9608       
\f2 \'a2\'c6\'a2\'c6
\f1 \uc0\u9608 \u9608 \
  \uc0\u9608 \u9608   \u9608 \u9608     \u9608 \u9608     \u9608 \u9608     \u9608 \u9608       \u9608 \u9608 \
    \uc0\u9608 \u9608 \u9608 \u9608     \u9608 \u9608     \u9608 \u9608       \u9608 \u9608   \u9608 \u9608   \
      \uc0\u9608 \u9608                   \u9608 \u9608   \u9608 \u9608   \
      \uc0\u9608 \u9608     \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608       \u9608 \u9608 \u9608 \u9608     \
        \uc0\u9608 \u9608               \u9608 \u9608 \u9608 \u9608       \
        \uc0\u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608       \
      \uc0\u9608 \u9608 \u9608 \u9608 
\f2 \'a2\'c6\'a2\'c6
\f1 \uc0\u9608 \u9608     \u9608 \u9608 
\f2 \'a2\'c6\'a2\'c6
\f1 \uc0\u9608 \u9608     \u9608 \u9608     \
    \uc0\u9608 \u9608   \u9608 \u9608 
\f2 \'a2\'c6\'a2\'c6
\f1 \uc0\u9608 \u9608     \u9608 \u9608 
\f2 \'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6
\f1 \uc0\u9608 \u9608     \u9608 \u9608   \
  \uc0\u9608 \u9608   \u9608 \u9608 
\f2 \'a2\'c6\'a2\'c6
\f1 \uc0\u9608 \u9608       \u9608 \u9608 
\f2 \'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6
\f1 \uc0\u9608 \u9608     \u9608 \u9608   \
  \uc0\u9608 \u9608   \u9608 \u9608 
\f2 \'a2\'c6\'a2\'c6
\f1 \uc0\u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 
\f2 \'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6
\f1 \uc0\u9608 \u9608     \u9608 \u9608 \
  \uc0\u9608 \u9608   \u9608 \u9608 
\f2 \'a2\'c6\'a2\'c6
\f1 \uc0\u9608 \u9608         \u9608 \u9608 
\f2 \'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6
\f1 \uc0\u9608 \u9608     \u9608 \u9608 \
    \uc0\u9608 \u9608 \u9608 \u9608 \u9608 \u9608     \u9608 \u9608       \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608   \
        \uc0\u9608 \u9608       \u9608 \u9608         \u9608 \u9608       \
      \uc0\u9608 \u9608 
\f2 \'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6
\f1 \uc0\u9608 \u9608 \u9608 \u9608 
\f2 \'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6
\f1 \uc0\u9608 \u9608 \u9608 \u9608 \u9608 \u9608       \
    \uc0\u9608 \u9608 
\f2 \'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6
\f1 \uc0\u9608 \u9608 
\f2 \'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6\'a2\'c6
\f1 \uc0\u9608 \u9608       \
    \uc0\u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608 \u9608       \
```\
\
* Located in /home/ubuntu/readme\
	* was able to navigate to ubuntu\'92s directory as airmanjoe\
	* Used cat readme}