WSL References 
---
---

## generic wsl commands 
- finding running distro 
``` bash 
wsl --list --running 
```

---

## How to make backup of existing Distro 

1- Get a full list of distro ` wsl -l -v`

2- for backup 
```bash 
 wsl --export (distribution) (filename.tar)

```

---
## How to restore the wsl distro 

```bash
wsl --import <DistributionName> <InstallLocation> <FileName>

```


---


## How to login to wsl with specific Username 

```bash
wsl -u <username> -d <DistroName>
```



## How to delete WSL Distro 
1- get the list of distros (for running stoped distros )
```bash
wsl -l -v
```
2- Run the following command with distro name
```bash
wsl --unregister <DistroName>
```

## Login with specific user and folder 

``` wsl -u abdullah -d MLVision --cd /home/abdullah ``` 

#### We can then use this above command as shortcut 