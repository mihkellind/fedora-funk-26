# fedora-funk-26

```
$ sudo dnf install nodejs
Last metadata expiration check: 0:01:36 ago on Sun 15 Oct 2017 11:46:11 AM EEST.
Dependencies resolved.
==========================================================================
 Package    Arch       Version                          Repository   Size
==========================================================================
Installing:
 nodejs     x86_64     1:6.11.3-1.fc26                  updates     4.7 M
Installing dependencies:
 libuv      x86_64     1:1.11.0-1.fc26                  fedora      112 k
Installing weak dependencies:
 npm        x86_64     1:3.10.10-1.6.11.3.1.fc26        updates     2.5 M

Transaction Summary
==========================================================================
Install  3 Packages

Total download size: 7.3 M
Installed size: 26 M
Is this ok [y/N]: y
Downloading Packages:
(1/3): libuv-1.11.0-1.fc26.x86_64.rpm     764 kB/s | 112 kB     00:00    
(2/3): nodejs-6.11.3-1.fc26.x86_64.rpm    3.1 MB/s | 4.7 MB     00:01    
(3/3): npm-3.10.10-1.6.11.3.1.fc26.x86_64 1.3 MB/s | 2.5 MB     00:01    
--------------------------------------------------------------------------
Total                                     1.8 MB/s | 7.3 MB     00:04     
Running transaction check
Transaction check succeeded.
Running transaction test
Transaction test succeeded.
Running transaction
  Preparing        :                                                  1/1 
  Installing       : libuv-1:1.11.0-1.fc26.x86_64                     1/3 
  Running scriptlet: libuv-1:1.11.0-1.fc26.x86_64                     1/3 
  Installing       : nodejs-1:6.11.3-1.fc26.x86_64                    2/3 
  Installing       : npm-1:3.10.10-1.6.11.3.1.fc26.x86_64             3/3 
  Running scriptlet: npm-1:3.10.10-1.6.11.3.1.fc26.x86_64             3/3 
  Verifying        : nodejs-1:6.11.3-1.fc26.x86_64                    1/3 
  Verifying        : libuv-1:1.11.0-1.fc26.x86_64                     2/3 
  Verifying        : npm-1:3.10.10-1.6.11.3.1.fc26.x86_64             3/3 

Installed:
  nodejs.x86_64 1:6.11.3-1.fc26    npm.x86_64 1:3.10.10-1.6.11.3.1.fc26   
  libuv.x86_64 1:1.11.0-1.fc26    

Complete!
```
