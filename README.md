# Megalist of methods to disable Hapara, Goguardian, etc

A page with info on how to disable common web filters and school spyware.

## List of known bypass methods and exploits

- [Ingot](https://fognetwork.github.io/Ingot/)  
  
  The successor of LTBEEF. Has a better UI.  
  Comes with all the same limitations as LTBEEF.  

- [LTBEEF](https://compactcow.com/ltbeef/)  
  
  What Ingot is based on. Opens a menu that lets you disable extensions.  
  Works if developer tools are blocked.  
  Won't work without JavaScript bookmarklets.  
  *Patched* in Chrome OS version 106 and above  

- [Chaos](https://xlak.github.io/chaos/)  
  
  Can disable force-installed extensions.  
  Uses a clever priveleg escalation attack.  
  Won't work if developer tools are completely disabled.  

- [Alphabetic](https://xlak.github.io/alphabetic/)  
  
  Opens hidden, unfiltered tabs that won't save in your history.  
  Doesn't affect the operation of monitoring software on other tabs, unlike most exploits.  
  Works without JavaScript bookmarklets.  
  Harder to get caught using this since teachers think they can still see all of your tabs.
  
- [GoGuardian close prevention](https://github.com/yeeteeyt/goguardian-bypass)  
  
  Does not hide anything from GoGuardian. Only prevents tabs from being closed.  
  
- [Hide tabs from Hapara](https://raw.githubusercontent.com/FreshPenguin112/bookmarklets/main/hapara%20tab%20hide%20XD) (Original source)[https://github.com/ConnorCodesatSchool/HaparaDelete/issues/2]
  
  Makes tabs show up as Google Drive tabs on the teacher dashboard.  
  Requires JavaScript bookmarklets to work.  
  This DOES NOT prevent Hapara from capturing your screen and teachers will see the real tab if they look at the screenshot view.  

## Proxy and Game Sites

- [Titanium Network](https://github.com/titaniumnetwork-dev)
- [Holy Unblocker](https://holyubofficial.net/) [Alt link](https://website-aio-e9x.koyeb.app/1.html)
- [Hypertabs](https://hypertabs.cc/)
- [Incognito](https://incog.dev/)
- [Taco Proxy](https://izhdh.sse.codesandbox.io/)
  
  Good at bypassing many web filters.  
  Join the Titanium Network Discord server for more links in case these are blocked.
  
- [3kh0 Unblocked Games](https://3kh0.github.io/)
  
  Hosts a lot of unblocked games.  
  Unfortunately it has lots of ads.  
  
- [Cool Math Games](https://www.coolmathgames.com/)
  
  This one's a classic.
  
- [Krunker.io Official Proxy](https://browserfps.com/)
  
  Play a fun FPS game in you browser.

## List of bypass methods by software
This is a list of web filters and spyware, as well as known methods to bypass them.

### Hapara Highlights
- Chaos
- Alphabetic
- LTBEEF
- Ingot
### Hapara Filter
Hapara Filter is actually just a rebranded version of the Deledao extension.  
It uses AI to detect sites that schools don't want you going on.  
That means the vast majority of proxy sites and unblocked games will not work without disabling it first.  
- Chaos
- Alphabetic (Can bypass it without disabling it)
- LTBEEF
- Ingot
### iBoss
Repl.it is apparently blocked by IP on iBoss because it is frequently used to unblock games.  
This is strange because many CS classes depend on Repl.it.  
- Alphabetic

## Useful Resources
[HeroHACK Academy of Hacking](https://sites.google.com/view/hackingacademybypro/home) (Contains lots of hints on how to find bypass methods)  
[LTBEEF Github Page](https://github.com/3kh0/ext-remover) (Source code for LTBEEF. Contains a funny message for sysadmins.)  
[Ingot Github Page](https://github.com/FogNetwork/Ingot) (Source code for Ingot.)  
[TitaniumNetwork Discord](https://discord.gg/unblock) (Join to get proxy links)  
[k12sysadmin on Reddit](https://reddit.com/r/k12sysadmin) (See what the sysadmins are talking about)  

## Contributing

This project aims to compile a list of known methods to get around web filters and school spyware. If you know of anything that is not covered here, please open an issue or a pull request.
