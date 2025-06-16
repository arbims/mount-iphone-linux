# procedure d'instalation et  mountage iphone

* Instalation des libs 
```
sudo dnf install install ifuse libimobiledevice libusbmuxd usbmuxd gvfs-afc
```
* creation dossier mountage

```
mkdir -p ~/iphone
```

* mounter l'iphone

```
ifuse ~/iphone
```

* demounter l'iphone

```
fusermount -u ~/iphone
```
