# DIHHHHH (rice 6.9.5)


<p align="center">
  <img src="./img/norise.png" alt="2" width="25%">
</p>
<p align="center">
  <img src="./img/deobf.jpg" alt="1" width="20%" />
  <img src="./img/deobf2.jpg" alt="2" width="20%" />
  <img src="./img/deobf3.jpg" alt="3" width="20%" />
  <img src="./img/heavy.jpg" alt="4" width="20%" />
</p>


## requirements

- JDK 21+
- betteh IQ

## modify

full offline, deobf, rename, fix, patch auth, add toggle and more....

## build

```
./gradlew clientJar
```

output: `build/dist/rise-client.jar`

## runnnnnnnnnn

```
./gradlew run
```

or directly (run `./gradlew gameDir` once first, see below):

```
java -Drise.gameDir=run -Djava.library.path=run/natives \
     -cp build/dist/rise-client.jar:libs/libraries.jar Start
```

## IntelliJ IDEA

1. open the project folder, wait for the gradle sync.
2. set the project SDK to JDK 21+.
3. select the **Rise Client** run configuration (committed in `.run/`) and hit run.

## system properties

all default to off.

| property | effect |
|---|---|
| `-Drise.auth.username=<name>` | username for the auth entry point |
| `-Drise.auth.autologin=true` | skip the login screen |
| `-Drise.gameDir=<path>` | game directory |
| `-Drise.protection.anticrack=true` | anti-crack environment scan |
| `-Drise.net.remotescripts=true` | remote script/config download |
| `-Drise.net.altservice=true` | alt-account service |
| `-Drise.net.versioncheck=true` | update gate on the login screen |

## 67

## kk

- **original obfuscated client:** RiseClient 6.9.5
- **some deobfuscation, symbol recovery:** completed by Claude™ and Codex™ under human supervision
- **devirtualization, flowdeobf, deobf tool:** anonymous™
- **Java Deobfuscator**
- **Recaf**
- **[VMProtect](https://vmpsoft.com/)** (demutation and devirtualization??!?!?!)
- **custom java obfuscator** (copied from zkm???)
- **RiseJDK-22.0.2** (ruthlessly modified)
- **Rise-vm😂** (funny)
- **[ViaVersionMCP/ViaMCP](https://github.com/ViaVersionMCP/ViaMCP)** — Licensed under GNU General Public License v3.0 / relevant open-source license


## legal & disclaimers

- **Minecraft Trademarks:** *Minecraft* is a trademark of Mojang Studios / Microsoft Corporation.  
- **Affiliation:** This project is an independent community development and is **NOT AN OFFICIAL MINECRAFT PRODUCT. NOT APPROVED BY OR ASSOCIATED WITH MOJANG OR MICROSOFT.**  
- **Assets & Code:** No proprietary Minecraft assets or un-obfuscated original Mojang source code are distributed directly within this repository. (All game assets belong to their respective owners). 

## Six Seven
