# LUDUS Templates

These directories are self-contained Ludus templates.

For more information see: https://docs.ludus.cloud/docs/templates

Here are some templates I'm using to get my ranges up.


## Easy template installation steps

1. Clone this repository

`git clone https://github.com/Croko-fr/ludus-templates.git`

2. Enter the directory

`cd ludus-templates`

3. Add the templates

```bash
ludus templates build -n almalinux-8-x64-fr-server-template
ludus templates build -n almalinux-9-x64-fr-server-template
for filename in *-*; do ludus template add -d $filename; done;
```

4. Build the templates

```bash
ludus templates build -n almalinux-8-x64-fr-server-template
[INFO]  Template building started - this will take a while. Building 1 template(s) at a time.
```

5. Look at the install logs

```bash
ludus templates logs -f
```

## Templates Verified

- French
  - Windows
    - [x] win10-22h2-x64-fr-enterprise
    - [x] win11-22h2-x64-fr-enterprise
    - [x] win2016-server-x64-fr
    - [x] win2019-server-x64-fr
    - [x] win2022-server-x64-fr
  - Linux
    - [x] almalinux-8-x64-fr-server
    - [x] almalinux-9-x64-fr-server
    - [x] debian-11-x64-fr-server
    - [x] debian-12-x64-fr-server
    - [x] rocky-8-x64-fr-server
    - [x] rocky-9-x64-fr-server
    - [x] ubuntu-20.04-x64-fr-server
    - [x] ubuntu-22.04-x64-fr-server
    - [x] ubuntu-24.04-x64-fr-desktop

- English
  - Windows
  - Linux
    - [x] almalinux-8-x64-us-server
    - [x] almalinux-9-x64-us-server
    - [x] debian-11-x64-us-server
    - [x] debian-12-x64-us-server

## LUDUS native templates

> From LUDUS github with language change, native template renamed to us and made standalone if needed
> means removed common direcory reference and changed iso

- English
  - Windows
    - [x] win10-22h2-x64-us-enterprise
    - [x] win2022-server-x64-us
  - Linux
    - [x] almalinux-8-x64-us-server
    - [x] almalinux-9-x64-us-server
    - [x] rocky-8-x64-us-server
    - [x] rocky-9-x64-us-server

## Templates to come

- Problem with apt-update
    - [ ] kali-2024-3-x64-us-desktop
    - [ ] kali-2024-3-x64-fr-desktop

- From LUDUS github with language change and native template renaming and made standalone if needed :
    - [ ] win10-21h1-x64-us-enterprise
    - [ ] win10-21h1-x64-fr-enterprise
    - [ ] win11-22h2-x64-us-enterprise
    - [ ] win11-22h2-x64-fr-enterprise
    - [ ] win11-23h2-x64-us-enterprise
    - [ ] win11-23h2-x64-fr-enterprise
    - [ ] win2012-r2-server-x64-us
    - [ ] win2012-r2-server-x64-fr
    - [ ] win2019-server-x64-us-no-security-updates
    - [ ] win2019-server-x64-fr-no-security-updates
