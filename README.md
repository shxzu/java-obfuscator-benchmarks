# Info
**THIS REPO IS STILL UNDER DEVELOPMENT PLEASE LEAVE ISSUES IF THERE IS ANY ERRORS!!**

This repository is dedicated to benchmarking obfuscators and the way they behave, perform, and what abilities they have. More detailed benchmarking and graphing will be done soon. Please create an issue if errors occur within any part of this benchmarking.

Created by sinxkyuna. Any duplicates or usage without proper credit will be **DMCAed!**

# Descriptions of what the obfuscators did to the JARS.

*All obfuscators use the most agressive configurations!!*

* ZKM 21 Crack - I've noticed ZKM 21 is not horrible. Recaf shows errors but in assembly mode it doesn't, this can make easy cracks if authentication is not great or badly coded. No crasher on any decompiler though. Added extra classes to throw off someone who's trying to reverse engineer. The flow obfuscation is the best out there right now. In terms of customizabilty and ease-of-access, it's also the best. Overall pretty hard to read without any modifications as well. Definitely a really good choice!

* SB27 - What can I say, for a free and old obfuscator it's not bad. Still don't use it of course, but it's not garbage. Like a lot of others, it throws errors in Recaf but in assembly mode it saves and such without any errors. Code is readable, not un-compiled java readable but still quite readable. Also adds WAY too many code comments. I would probably only use this for applications that are launchers or basic games as per the base JAR which is Snake.

* Allatori v9.2 - Honestly, this is in my opinion the BEST obfuscator out there. Recaf takes FOREVER to decompile, a decompiler timeout happens most times, and errors within the editor. I haven't tested assembly mode but considering a lot of others fold to it I'm guess Allatori does too. Allatori adds a bunch of X's and Y's to the targeted classes which causes the Recaf stuff. It also adds a lot of local variables confusing the person reverse engineering the JAR even more. The flow obfuscation is really good too. Also can crash a few decompilers. Personally I would choose Allatori for a all-purpose obfuscator which would take crackers ages to crack as long as your authentication is well coded.

*Thanks to @hexadeciman for creating the base JAR of SnakeGame!*
