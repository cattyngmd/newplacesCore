# ExploitFixer for /new places/
Это самопал из разных фиксов из плагинов адаптированных под мои цели для моего сервера /new places/

Что он исправляет:
1. AntiBookExploit - запрещает писать Unicode в книги, только кириллица и латиница в соотвествии с кодировкой ISO-8859-5. Для противодействия создания BookBan или ChunkDupe.
2. AntiBurrow - противодействует читу Burrow который не может ловить NoCheatPlus
3. AntiBowBomb - противодействует эксплоиту One Tap (Bow Bomb) который позволяет убивать/"попнуть" тотем с одного высрела, этот эксплоит не может ловить эффективно NoCheatPlus
4. AntiPacketExploit - противодействует читам которые базируются на пакетном принципе работы, в частности на полет.
5. AntiRedstone - противодействует лаг машинам, отключая все редстоун механизмы на сервере при низком TPS сервера.

Есть 2 версии.
Anarchy - для нашего анархичного сервера, и CPVP - для нашего CPVP сервера.

Проект легко собирается из под IntelliJ IDEA в Maven

Исходный код модулей был взят из:
https://github.com/moom0o/AnarchyExploitFixes и https://github.com/Bleep0/AntiBookBan

Я не претендую на авторство кода.
