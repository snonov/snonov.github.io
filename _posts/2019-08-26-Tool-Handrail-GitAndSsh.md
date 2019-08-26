---
layout: post
title: "Tool handrail Git and Ssh"
date: 2019-08-26
tags : Tool Handrail Git Ssh
---

## Some Git commands (remote operations)

To check your remote from local : git remote -v     
To change on local refers remote host : git remote set-url origin git@gitlab.example.com:my-group/my-project.git     

## Some ssh commands

To get ssh trace (debug, verbose)    
GIT_TRACE=1 GIT_SSH_COMMAND="ssh -vvv" git clone git@gitlab.example.com:my-group/my-project.git

Generate a new key    
ssh-keygen -t rsa -C "userName"

Test host access
ssh gitlab.example.com -v     
or openssl s_client -connect gitlab.example.com:port     

## remote migration

You can keep same ssh key (or generate and use a new one). Keeping same check :
* config file (cat ~/.ssh/config), there should be an entry with new remote host specifying "IdentityFile ~/.ssh/MyPrivateKey" on it    
* known_host (cat ~/.ssh/known_hosts) should have an entry with new remote host (check add finger print to add)    

## Some Ssh cheasheet and infos    

Cheatsheet :    
* [ssh cheat sheet](https://cheatsheet.dennyzhang.com/cheatsheet-ssh-a4)    
* [another ssh cheat sheet](http://pentestmonkey.net/cheat-sheet/ssh-cheat-sheet)  
* [one more Ssh cheat sheet](https://lzone.de/cheat-sheet/SSH)   

Specific :      
* [ssh config file](https://nerderati.com/2011/03/17/simplify-your-life-with-an-ssh-config-file/)    
* [using ssh config file](https://linuxize.com/post/using-the-ssh-config-file/)    
* [Add ssh finger print](https://www.techrepublic.com/article/how-to-easily-add-an-ssh-fingerprint-to-your-knownhosts-file-in-linux/)     

Others :   
* [GitHub ssh help](https://help.github.com/en/articles/about-ssh)        
* [GitLab ssh help](https://docs.gitlab.com/ee/ssh/)     
* [Bitbucket ssh](https://confluence.atlassian.com/bitbucket/ssh-keys-935365775.html)         



