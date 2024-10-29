
# BetterCommands

[![Build Status](https://ci.thom.club/job/TheExoticsMod/job/master/badge/icon)](https://ci.thom.club/job/TheExoticsMod/job/master/) [![Contributors](https://img.shields.io/github/contributors/TGWaffles/TheExoticsMod?&logo=GitHub)](https://github.com/TGWaffles/TheExoticsMod/graphs/contributors) [![Jenkins Coverage](https://img.shields.io/jenkins/coverage/jacoco?jobUrl=https%3A%2F%2Fci.thom.club%2Fjob%2FTheExoticsMod%2Fjob%2Fmaster)](https://ci.thom.club/job/TheExoticsMod/job/master/jacoco/) [![Jenkins tests](https://img.shields.io/jenkins/tests?compact_message&jobUrl=https%3A%2F%2Fci.thom.club%2Fjob%2FTheExoticsMod%2Fjob%2Fmaster)](https://ci.thom.club/job/TheExoticsMod/job/master/lastBuild/testReport/)

---

__BetterCommands__

BetterCommands is an open source, community-led mod for Hypixel Skyblock.


BetterCommands also includes qol features such as: 
-Dungeon secret routes (routes recorded by cata 61) COMING SOON
-Slayer qol COMING SOON
-Farming qol COMING SOON
-Dungeons qol COMING SOON
-Party commands such as (!warp, !party, !disband)




---
## How to build?

### Protoc Files

`protoc -I . --java_out annotate_code:src/main/java/ clientMessages.proto`

`protoc -I . --java_out annotate_code:src/main/java/ serverMessages.proto`
