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
    - [x] win10-21h2-x64-fr-enterprise
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
    - [x] kali-2024-4-x64-fr-desktop
    - [x] kali-2024-4-x64-fr-desktop-pentest
    - [x] rocky-8-x64-fr-server
    - [x] rocky-9-x64-fr-server
    - [x] ubuntu-20.04-x64-fr-server
    - [x] ubuntu-22.04-x64-fr-server
    - [x] ubuntu-24.04-x64-fr-desktop

- English
  - Windows
    - [x] win10-21h2-x64-us-enterprise
    - [x] win2016-server-x64-us
  - Linux
    - [x] almalinux-8-x64-us-server
    - [x] almalinux-9-x64-us-server
    - [x] debian-11-x64-us-server
    - [x] debian-12-x64-us-server
    - [x] kali-2024-4-x64-us-desktop-pentest

## LUDUS native templates

> From LUDUS github with language change, native template renamed to us and made standalone if needed
> means removed common directory reference and changed to iso and adding necessary files

- English
  - Windows
    - [x] win10-22h2-x64-us-enterprise
    - [x] win2019-server-x64-us
    - [x] win2022-server-x64-us
  - Linux
    - [x] almalinux-8-x64-us-server
    - [x] almalinux-9-x64-us-server
    - [x] kali-2024-4-x64-us-desktop ( [patched by Erik@Ludus](https://gitlab.com/badsectorlabs/ludus/-/commit/9539122a664284beeb833edea2c465dc497fef15) )
    - [x] rocky-8-x64-us-server
    - [x] rocky-9-x64-us-server

## Templates to come

- From LUDUS github with language change and native template renaming and made standalone if needed :
    - [ ] win11-22h2-x64-us-enterprise
    - [ ] win11-22h2-x64-fr-enterprise
    - [ ] win11-23h2-x64-us-enterprise
    - [ ] win11-23h2-x64-fr-enterprise
    - [ ] win2012-r2-server-x64-us
    - [ ] win2012-r2-server-x64-fr
    - [ ] win2019-server-x64-us-no-security-updates
    - [ ] win2019-server-x64-fr-no-security-updates

## Templates being tested

- Debian 10
  - debian-10-7-x64-fr-server
  - debian-10-7-x64-us-server
  - debian-10-8-x64-fr-server
  - debian-10-8-x64-us-server
  - debian-10-9-x64-fr-server
  - debian-10-9-x64-us-server
  - debian-10-10-x64-fr-server
  - debian-10-10-x64-us-server
  - debian-10-11-x64-fr-server
  - debian-10-11-x64-us-server
  - debian-10-12-x64-fr-server
  - debian-10-12-x64-us-server
  - debian-10-13-x64-fr-server
  - debian-10-13-x64-us-server
- Debian 11
  - debian-11-0-x64-fr-server
  - debian-11-0-x64-us-server
  - debian-11-1-x64-fr-server
  - debian-11-1-x64-us-server
  - debian-11-2-x64-fr-server
  - debian-11-2-x64-us-server
  - debian-11-3-x64-fr-server
  - debian-11-3-x64-us-server
  - debian-11-4-x64-fr-server
  - debian-11-4-x64-us-server
  - debian-11-5-x64-fr-server
  - debian-11-5-x64-us-server
  - debian-11-6-x64-fr-server
  - debian-11-6-x64-us-server
  - debian-11-7-x64-fr-server
  - debian-11-7-x64-us-server
  - debian-11-8-x64-fr-server
  - debian-11-8-x64-us-server
  - debian-11-9-x64-fr-server
  - debian-11-9-x64-us-server
  - debian-11-10-x64-fr-server
  - debian-11-10-x64-us-server
  - debian-11-11-x64-fr-server
  - debian-11-11-x64-us-server
- Debian 12
  - debian-12-0-x64-fr-server
  - debian-12-0-x64-us-server
  - debian-12-1-x64-fr-server
  - debian-12-1-x64-us-server
  - debian-12-2-x64-fr-server
  - debian-12-2-x64-us-server
  - debian-12-4-x64-fr-server
  - debian-12-4-x64-us-server
  - debian-12-5-x64-fr-server
  - debian-12-5-x64-us-server
  - debian-12-6-x64-fr-server
  - debian-12-6-x64-us-server
  - debian-12-7-x64-fr-server
  - debian-12-7-x64-us-server
  - debian-12-8-x64-fr-server
  - debian-12-8-x64-us-server