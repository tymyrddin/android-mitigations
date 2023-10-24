# Edit hosts file

The hosts file is a system file on a device that lets you map specific domain names to an IP address. If you want 
to add new entries to the hosts file, you’ll need the IP address of the server that you want to map a hostname to.

    XXX.XXX.XXX.XXX some.domain.name 

The hosts file lets you override DNS entries for any domain name. There are lists of common ad networks and 
tracking servers available online which you can use to keep an up-to-date list of sites to block. Blocking is achieved 
by setting the IP address of the ad networks to a loopback address like 127.0.0.1 which will not return anything. 
There are lists of common ad networks and tracking servers available online which you can use to keep an up-to-date 
list of sites to block. 

If your device is infected with malware, then your hosts file may be compromised to included unknown entries for known 
domain names. *That* is NOT the IP address of your bank! This type of DNS attack is known as DNS pharming, and checking 
your `hosts` file can uncover potential infection.

For Android there is a way using [Android Debug Bridge (adb)](https://testlab.tymyrddin.dev/docs/mobile/adb):

1. Open a terminal window.
2. Pull the hosts file out of the phone to your PC.
3. Edit it.
4. disable READ_ONLY of SYSTEM

```text
$ su
# mount -o rw,remount /system
```

5. Push the file back.
6. Put SYSTEM back to READ_ONLY: 

```text
# mount -o ro,remount /system
```

