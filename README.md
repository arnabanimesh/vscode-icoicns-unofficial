# VSCode Unofficial icon repo

Main motivation of creating this This repository aims to assist people in creation of official look alike file icons for VSCode. I have created an icon for Rust lang, since I happen to use that a lot. I have also uploaded templates which are used by original VSCode icons (am not 100% sure about the resolutions used by the mac icon since I happen to use Windows). You guys can download and modify it as per your tastes.

*Please help increase the database of this repository so that it may help others change the file icons for VSCode.*

---

## Steps to change the file icon:

1. In order to change the file icon for a specific file type, look for a registry key:

```
HKEY_USERS\S-1-5-21-{some id}\Software\Classes\VSCode.<file ext>\DefaultIcon
```

2. Change the icon path in your registry key to your preferable icon path (Windows and Mac only supports `.ico` and `.icns` file types respectively).

If there is any way of preventing registry modification post VS Code update or if the extension is not there in the registry, maybe somebody can suggest some other way ~~(edit this readme here)~~.

