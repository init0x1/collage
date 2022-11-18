packet tracer 

## Enter privileged EXEC mode.
```
enable
```
## Enter globle configration mode.
```
configure terminal
```
## Access config line mode 
```
line console 0
```
## Examine the current switch configuration.
```
show running-config
```
## display the current contents of non-volatile random-access memory (NVRAM).
```
show startup-config
```
## Assign a name to a switch.
### you need to Enter globle configration mode
```
hostname $name
```
## Secure access to the console line.
### you need to Enter config line mode.
```
password $password
```
```
login
```
to enable password checking `login`

## Secure privileged mode access.
### this done in globle configration mode.
```
enable password $password
```
## Configure an encrypted password to secure access to privileged mode.
### this done in globle configration mode.
```
enable secret $secretpassword
```
## Encrypt the enable and console passwords.
### this done in globle configration mode.
```
service password-encryption
```
## Configure a message of the day (MOTD) banner.
### this done in globle configration mode.
```
banner motd $message here$
```
## Save and Verify Configuration Files to NVRAM
### this done in privileged EXEC mode.
```
copy running-config startup-config
```
