# /new places/ Core
![изображение](https://user-images.githubusercontent.com/82046704/172054915-33821ffe-ba30-43af-a9f8-9ed0a8511ef3.png)

Это самопал из разных фиксов из плагинов адаптированных под мои цели для моего сервера /new places/

Работает на 1.18.2
Для работы требуется ProtocolLib 4.8.0

Что он может?
1. AntiBookExploit - запрещает писать Unicode в книги, только кириллица и латиница в соотвествии с кодировкой ISO-8859-5. Для противодействия создания BookBan или ChunkDupe.
2. AntiBurrow - противодействует читу Burrow который не может ловить NoCheatPlus
3. AnityBowBomb - противодействует эксплоиту One Tap (Bow Bomb) который позволяет убивать/"попнуть" тотем с одного высрела, этот эксплоит не может ловить эффективно NoCheatPlus
4. ProtocolLib Module - противодействует читам которые базируются на пакетном принципе работы, в частности на полет (PacketFly, BoatFly, CraftingRecipeLagExploit). Который не может ловить NCP
5. Redstone Module - противодействует лаг машинам, отключая все редстоун механизмы на сервере при низком TPS сервера.
6. AntiNetherRoof - противодействует попыткам передвигаться по крыше измерения Nether, просто не позволяя игрокам передвигаться.
7. PacketElytraFly - Для противодействия пакетным ElytraFly из Future, Konas, KamiBlue, RusherHack. Который не может ловить NCP

Есть 2 версии.
Anarchy - для нашего анархичного сервера, и CPVP - для нашего CPVP сервера.

Проект легко собирается из IntelliJ IDEA или Apache Netbeans в Maven
