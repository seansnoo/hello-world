## First Flag
* welcome~padawan
* located in /home/airmanjoe/readme
	* Just used cat readme

## Second Flag
* nananananananana+batman
* located in /home/airmanjoe/hidden/.cantseeme
	* Found using ls -lah
	* Used cat .cantseeme

## Third Flag
* Low/orbit
* located in /home/airmanjoe/'spaces in this filename'
	* Used cat \'91spaces then tabbed to auto complete filename.

## Fourth Flag 
* calamity-zebra
* located in /home/airmanjoe/execute_me
	* used ls -lah, and saw that file was an executable.
	* Ran ./execute_me

## Fifth Flag
* cr18\{4468282076f753640f3574392c730758\}
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
## Ubuntu\s Flag
``` 
sneaky, I like it.  Unfortunately your flags are in another castle...

            ██████████            
        ████          ████        
      ██      ▒▒▒▒▒▒      ██      
    ██      ▒▒▒▒▒▒▒▒▒▒      ██    
    ██      ▒▒▒▒▒▒▒▒▒▒        ██  
  ██▒▒      ▒▒▒▒▒▒▒▒▒▒      ▒▒██  
  ██▒▒▒▒      ▒▒▒▒▒▒        ▒▒▒▒██
  ██▒▒▒▒                    ▒▒▒▒██
  ██▒▒      ████████        ▒▒▒▒██
  ██    ██████    ██████      ▒▒██
  ██  ██    ██    ██    ██      ██
    ████    ██    ██      ██  ██  
      ██                  ██  ██  
      ██    ████████      ████    
        ██              ████      
        ████████████████████      
      ████▒▒██    ██▒▒██    ██    
    ██  ██▒▒██    ██▒▒▒▒██    ██  
  ██  ██▒▒██      ██▒▒▒▒██    ██  
  ██  ██▒▒██████████▒▒▒▒▒▒██    ██
  ██  ██▒▒██        ██▒▒▒▒██    ██
    ██████    ██      ██████████  
        ██      ██        ██      
      ██▒▒▒▒▒▒████▒▒▒▒██████      
    ██▒▒▒▒▒▒▒▒██▒▒▒▒▒▒▒▒▒▒██      
    ████████████████████████      

```

* Located in /home/ubuntu/readme
	* was able to navigate to ubuntu's directory as airmanjoe
	* Used cat readme
