LCEMP is my minecraft legacy console source fork that enables LAN multiplayer hosting
features:
fully working mulitplayer (breaking,placing,kick system, up to 8 players modificable on source)
keyboard and mouse support
gamma fixed
fullscreen support

launch arguments

-name username (sets username)
-ip targetip (if the advertiser doesnt work or you cant reach it, you can supply an ip manually so you can join)
-port targetport (if you changed port you can change it with launch arg)

if you use on other LCE projects then please credit me, be aware that my code is not the best ever and might have a ton of issues (im learning c++)
if you find any issue please PR and i will gladly merge it

this is NOT the full source code, you need the asset files from another place

you need:

Directory	Content
Minecraft.Client/music/	Music files (.binka) — calm, creative, nether, menu, hal, etc.
Minecraft.Client/Common/Media/	UI (.swf), Graphics (.png), Sound (.wav), Fonts, Localization, XUI scenes, .arc media archives
Minecraft.Client/Common/res/	Game textures — terrain, gui, mob, item, font, art, particles, etc.
Minecraft.Client/Common/DummyTexturePack/	Default texture pack resources
Minecraft.Client/DurangoMedia/	Xbox One platform media (DLC, sounds, strings)
Minecraft.Client/OrbisMedia/	PS4 platform media
Minecraft.Client/PS3Media/	PS3 platform media
Minecraft.Client/PSVitaMedia/	PS Vita platform media
Minecraft.Client/Windows64Media/	Windows 64 platform media
Minecraft.Client/redist64/	Miles Sound System redistributables (binkawin64.asi, mss64*.flt)
Minecraft.Client/PS3_GAME/	PS3 game package (PARAM.SFO, ICON0.PNG, etc.)
Minecraft.Client/PS4_GAME/	PS4 game package (eboot, modules, sounds)
Minecraft.Client/sce_sys/	PS Vita system files (icons, trophies, param)
Minecraft.Client/TROPDIR/	Trophy data
**/4JLibs/	4J Studios proprietary libraries (all platforms)
**/Miles/	Miles Sound System middleware (RAD Game Tools)
**/Iggy/	Iggy/Scaleform UI middleware
**/Sentient/	Sentient middleware
Minecraft.Client/PS3/PS3Extras/boost_*/	Boost C++ libraries (1.53.0)

a easy way to install this is just replacing with another source folder

made by notpies
Minecraft.Client/PS3/PS3Extras/DirectX/	DirectX math headers
Minecraft.Client/PS3/PS3Extras/HeapInspector/	Heap inspector static libs
Minecraft.Client/Common/Network/Sony/	Sony remote storage libraries (.a)
