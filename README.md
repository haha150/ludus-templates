# LUDUS Templates

These directories are self-contained Ludus templates.

For more information see: https://docs.ludus.cloud/docs/templates

Here are some templates I'm using to get my ranges up.


## Easy template installation steps

1. Clone this repository

`git clone https://github.com/haha150/ludus-templates.git`

2. Enter the directory

`cd ludus-templates`

3. Add the templates from directory

```bash
ludus templates add -d Debian/debian-10-10-x64-us-server
ludus templates add -d Debian/debian-12-8-x64-us-server
for filename in *-*; do ludus template add -d $filename; done;
```

4. Show templates list

```bash
ludus templates list
+----------------------------------------------------+-------+
|                      TEMPLATE                      | BUILT |
+----------------------------------------------------+-------+
| debian-10-10-x64-us-server-template                | FALSE |
| debian-12-8-x64-us-server-template                 | FALSE |
+----------------------------------------------------+-------+
```

5. Build the templates

```bash
ludus templates build -n debian-10-10-x64-us-server-template
[INFO]  Template building started - this will take a while. Building 1 template(s) at a time.
```

6. Look at the install logs

```bash
ludus templates logs -f
```

7. After the building is succesfull

```bash
=>================
=> Build complete!
=>================
^C

ludus templates list
+----------------------------------------------------+-------+
|                      TEMPLATE                      | BUILT |
+----------------------------------------------------+-------+
| debian-10-10-x64-us-server-template                | TRUE  |
| debian-12-8-x64-us-server-template                 | FALSE |
+----------------------------------------------------+-------+
```

## BEEING TESTED

| OS type | Distribution | Version | Languages | Info |
|:---:|:---:|:---:|:---:|:---:|
| Microsoft | Windows Server | 2012 R2 | us | |
| Linux | Kali | 2024.4 | us | Desktop , Recon |
| Linux | Kali | 2024.4 | us | Desktop , Web |

## TEMPLATES COVERAGE

### WINDOWS

| OS type | Distribution | Version | Languages | Info |
|:---:|:---:|:---:|:---:|:---:|
| Microsoft | Windows 10 | 21H2 LTSC | us | |
| Microsoft | Windows 10 | 22H2 | us | |
| Microsoft | Windows 11 | 22H2 | us | |
| Microsoft | Windows 11 | 23H2 | us | | 
| Microsoft | Windows Server | 2016 | us | |
| Microsoft | Windows Server | 2019 | us | |
| Microsoft | Windows Server | 2019 | us | No security updates |
| Microsoft | Windows Server | 2022 | us | |

### LINUX - ALMALINUX

| OS type | Distribution | Release | Version | Languages | Contributor |
|:---:|:---:|:---:|:---:|:---:|:---:|
| Linux | Almalinux | 8.10 | Server | us | |
| Linux | Almalinux | 9.1 | Server | us | |
| Linux | Almalinux | 9.2 | Server | us | |
| Linux | Almalinux | 9.3 | Server | us | |
| Linux | Almalinux | 9.4 | Server | us | |
| Linux | Almalinux | 9.5 | Server | us | [dygland](https://github.com/dygland) |

### LINUX - CENTOS

| OS type | Distribution | Release | Version | Languages |
|:---:|:---:|:---:|:---:|:---:|
| Linux | CentOS | 7.8.2003 | Server | us |
| Linux | CentOS | 7.9.2009 | Server | us |
| Linux | CentOS | 8.0.1905 | Server | us |
| Linux | CentOS | 8.1.1911 | Server | us |
| Linux | CentOS | 8.2.2004 | Server | us |
| Linux | CentOS | 8.3.2011 | Server | us |
| Linux | CentOS | 8.4.2105 | Server | us |
| Linux | CentOS | 8.5.2111 | Server | us |
| Linux | CentOS | 8-Stream | Server | us |

### LINUX - DEBIAN

| OS type | Distribution | Release | Version | Languages |
|:---:|:---:|:---:|:---:|:---:|
| Linux | Debian | 10.7 | Server | us |
| Linux | Debian | 10.8 | Server | us |
| Linux | Debian | 10.9 | Server | us |
| Linux | Debian | 10.10 | Server | us |
| Linux | Debian | 10.11 | Server | us |
| Linux | Debian | 10.12 | Server | us |
| Linux | Debian | 10.13 | Server | us |
| Linux | Debian | 11.0 | Server | us |
| Linux | Debian | 11.1 | Server | us |
| Linux | Debian | 11.2 | Server | us |
| Linux | Debian | 11.3 | Server | us |
| Linux | Debian | 11.4 | Server | us |
| Linux | Debian | 11.5 | Server | us |
| Linux | Debian | 11.6 | Server | us |
| Linux | Debian | 11.7 | Server | us |
| Linux | Debian | 11.8 | Server | us |
| Linux | Debian | 11.9 | Server | us |
| Linux | Debian | 11.10 | Server | us |
| Linux | Debian | 11.11 | Server | us |
| Linux | Debian | 12.0 | Server | us |
| Linux | Debian | 12.1 | Server | us |
| Linux | Debian | 12.2 | Server | us |
| Linux | Debian | 12.3 | Server | us |
| Linux | Debian | 12.4 | Server | us |
| Linux | Debian | 12.5 | Server | us |
| Linux | Debian | 12.6 | Server | us |
| Linux | Debian | 12.7 | Server | us |
| Linux | Debian | 12.8 | Server | us |
| Linux | Debian | 12.9 | Server | us |

### LINUX - KALI

| OS type | Distribution | Release | Version | Languages |
|:---:|:---:|:---:|:---:|:---:|
| Linux | Kali | 2024.4 | Desktop | us |
| Linux | Kali | 2024.4 | Desktop , Pentest | us |

### LINUX - ROCKY

| OS type | Distribution | Release | Version | Languages |
|:---:|:---:|:---:|:---:|:---:|
| Linux | Rocky | 8.10 | Server | us |
| Linux | Rocky | 9.5 | Server | us |

### LINUX - UBUNTU

| OS type | Distribution | Release | Version | Languages | Contributor |
|:---:|:---:|:---:|:---:|:---:|:---:|
| Linux | Ubuntu | 20.04.1 | Server | us | |
| Linux | Ubuntu | 22.04.1 | Server | us | |
| Linux | Ubuntu | 22.04.2 | Server | us | |
| Linux | Ubuntu | 22.04.3 | Server | us | |
| Linux | Ubuntu | 22.04.4 | Server | us | |
| Linux | Ubuntu | 22.04.5 | Server | us | |
| Linux | Ubuntu | 24.04.1 | Desktop | us | |
| Linux | Ubuntu | 24.04.1 | Server | us | [usack113](https://github.com/usack113) |
| Linux | Ubuntu | 24.04.2 | Desktop | us | |
| Linux | Ubuntu | 24.04.2 | Server | us | |
