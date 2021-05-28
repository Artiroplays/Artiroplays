---- Minecraft Crash Report ----
// I bet Cylons wouldn't have this problem.

Time: 11/15/20 11:04 AM
Description: Updating screen events

java.lang.IllegalArgumentException: Parameter 'directory' is not a directory
	at org.apache.commons.io.FileUtils.validateListFilesParameters(FileUtils.java:545)
	at org.apache.commons.io.FileUtils.listFiles(FileUtils.java:521)
	at bnm.i(SourceFile:222)
	at bnm.a(SourceFile:188)
	at bcy$3$1.a(SourceFile:1233)
	at awy.a(SourceFile:50)
	at axu.a(SourceFile:350)
	at axu.k(SourceFile:413)
	at axu.p(SourceFile:390)
	at ave.s(SourceFile:1498)
	at ave.av(SourceFile:889)
	at ave.a(SourceFile:325)
	at net.minecraft.client.main.Main.main(SourceFile:124)


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Stacktrace:
	at org.apache.commons.io.FileUtils.validateListFilesParameters(FileUtils.java:545)
	at org.apache.commons.io.FileUtils.listFiles(FileUtils.java:521)
	at bnm.i(SourceFile:222)
	at bnm.a(SourceFile:188)
	at bcy$3$1.a(SourceFile:1233)
	at awy.a(SourceFile:50)
	at axu.a(SourceFile:350)
	at axu.k(SourceFile:413)
	at axu.p(SourceFile:390)

-- Affected screen --
Details:
	Screen name: awy

-- Affected level --
Details:
	Level name: MpServer
	All players: 29 total; [bew['Artiro_plays'/8101940, l='MpServer', x=-61.30, y=81.00, z=-19.46], bex['rumppork'/114, l='MpServer', x=-61.31, y=93.09, z=-19.47], bex['Stelarity'/91, l='MpServer', x=62.50, y=82.16, z=-17.50], bex['harunoki86'/104, l='MpServer', x=62.31, y=81.94, z=20.69], bex['HANCRAFT'/107, l='MpServer', x=18.50, y=81.00, z=62.50], bex['Pick1ez'/98, l='MpServer', x=-19.69, y=82.06, z=62.31], bex['Jus2Kiwiii'/96, l='MpServer', x=70.50, y=81.00, z=-0.69], bex['NoHaxJustMineman'/99, l='MpServer', x=1.69, y=81.00, z=70.69], bex['Equesnell'/82, l='MpServer', x=-61.50, y=81.00, z=18.50], bex['Zipboing'/106, l='MpServer', x=-17.69, y=81.00, z=-61.69], bex['sweet_bacon1202'/100, l='MpServer', x=20.34, y=81.00, z=-61.50], bex['§cDgZgzR2Cg'/469, l='MpServer', x=-79.50, y=85.88, z=-12.91], bex['§cFlnR4Ga'/477, l='MpServer', x=-53.63, y=87.31, z=-8.84], bex['§c5Qb62mtnJEtB'/467, l='MpServer', x=-81.06, y=86.31, z=-42.38], bex['§cJBUqG2'/474, l='MpServer', x=-74.34, y=86.25, z=2.06], bex['§ct3XwGfoJBNq'/468, l='MpServer', x=-84.06, y=80.59, z=-26.41], bex['§cHIq9Exnqm'/470, l='MpServer', x=-81.22, y=84.25, z=3.66], bex['§c4n2cncFgxI5'/473, l='MpServer', x=-68.78, y=84.06, z=-8.66], bex['§ciOABH9aR'/471, l='MpServer', x=-69.31, y=83.27, z=-38.77], bex['§cGdmBzxx5ZH'/480, l='MpServer', x=-42.18, y=83.17, z=-29.11], bex['§cTeNa73hVRp'/479, l='MpServer', x=-41.50, y=78.66, z=-38.88], bex['§cV7YXgi3cu4JAO'/482, l='MpServer', x=-40.02, y=82.72, z=1.13], bex['§cP2EjONtgy8a'/481, l='MpServer', x=-42.97, y=80.58, z=-9.71], bex['§cNjfqXOMTqmWj'/476, l='MpServer', x=-49.25, y=82.09, z=-29.91], bex['§c5cfL0ONqkDH'/475, l='MpServer', x=-50.78, y=78.09, z=-37.72], bex['§c6bYv50WU'/478, l='MpServer', x=-51.33, y=81.29, z=1.89], bex['§c4rGSHr'/472, l='MpServer', x=-68.13, y=78.81, z=-29.47], bex['Mayu___'/531, l='MpServer', x=-69.50, y=81.00, z=1.50], bex['RiotRevoltz'/532, l='MpServer', x=-0.50, y=81.00, z=-69.50]]
	Chunk stats: MultiplayerChunkCache: 441, 441
	Level seed: 0
	Level generator: ID 01 - flat, ver 0. Features enabled: false
	Level generator options: 
	Level spawn location: 1180.00,4.00,-763.00 - World: (1180,4,-763), Chunk: (at 12,0,5 in 73,-48; contains blocks 1168,0,-768 to 1183,255,-753), Region: (2,-2; contains chunks 64,-64 to 95,-33, blocks 1024,0,-1024 to 1535,255,-513)
	Level time: 21178597 game time, 89 day time
	Level dimension: 0
	Level storage version: 0x00000 - Unknown?
	Level weather: Rain time: 0 (now: false), thunder time: 0 (now: false)
	Level game mode: Game mode: survival (ID 0). Hardcore: false. Cheats: false
	Forced entities: 71 total; [bew['Artiro_plays'/8101940, l='MpServer', x=-61.30, y=81.00, z=-19.46], bex['rumppork'/114, l='MpServer', x=-61.31, y=93.09, z=-19.47], bex['Stelarity'/91, l='MpServer', x=62.50, y=82.16, z=-17.50], bex['Mayu___'/531, l='MpServer', x=-69.50, y=81.00, z=1.50], bex['HANCRAFT'/107, l='MpServer', x=18.50, y=81.00, z=62.50], bex['RiotRevoltz'/532, l='MpServer', x=-0.50, y=81.00, z=-69.50], bex['Pick1ez'/98, l='MpServer', x=-19.69, y=82.06, z=62.31], bex['harunoki86'/104, l='MpServer', x=62.31, y=81.94, z=20.69], bex['Equesnell'/82, l='MpServer', x=-61.50, y=81.00, z=18.50], bex['Zipboing'/106, l='MpServer', x=-17.69, y=81.00, z=-61.69], bex['Jus2Kiwiii'/96, l='MpServer', x=70.50, y=81.00, z=-0.69], up['entity.LeashKnot.name'/538, l='MpServer', x=4.50, y=82.50, z=-64.50], bex['NoHaxJustMineman'/99, l='MpServer', x=1.69, y=81.00, z=70.69], vs['Giant'/539, l='MpServer', x=4.06, y=86.56, z=-66.22], tk['Bat'/540, l='MpServer', x=1.16, y=94.56, z=-68.25], bex['sweet_bacon1202'/100, l='MpServer', x=20.34, y=81.00, z=-61.50], up['entity.LeashKnot.name'/541, l='MpServer', x=-64.50, y=82.50, z=-3.50], vs['Giant'/542, l='MpServer', x=-66.22, y=86.56, z=-4.06], tk['Bat'/543, l='MpServer', x=-69.13, y=94.56, z=-6.06], bex['misterTNT1'/85, l='MpServer', x=-0.50, y=81.00, z=-69.50], bex['§cDgZgzR2Cg'/469, l='MpServer', x=-79.50, y=85.88, z=-12.91], bex['§cJBUqG2'/474, l='MpServer', x=-74.34, y=86.25, z=2.06], bex['§ct3XwGfoJBNq'/468, l='MpServer', x=-84.06, y=80.59, z=-26.41], bex['§cFlnR4Ga'/477, l='MpServer', x=-53.63, y=87.31, z=-8.84], bex['§c5Qb62mtnJEtB'/467, l='MpServer', x=-81.06, y=86.31, z=-42.38], bex['§ciOABH9aR'/471, l='MpServer', x=-69.31, y=83.27, z=-38.77], bex['§cGdmBzxx5ZH'/480, l='MpServer', x=-42.18, y=83.17, z=-29.11], bex['§cHIq9Exnqm'/470, l='MpServer', x=-81.22, y=84.25, z=3.66], bex['§c4n2cncFgxI5'/473, l='MpServer', x=-68.78, y=84.06, z=-8.66], bex['§cP2EjONtgy8a'/481, l='MpServer', x=-42.97, y=80.58, z=-9.71], bex['§cNjfqXOMTqmWj'/476, l='MpServer', x=-49.25, y=82.09, z=-29.91], bex['§cTeNa73hVRp'/479, l='MpServer', x=-41.50, y=78.66, z=-38.88], bex['§cV7YXgi3cu4JAO'/482, l='MpServer', x=-40.02, y=82.72, z=1.13], bex['§c4rGSHr'/472, l='MpServer', x=-68.13, y=78.81, z=-29.47], bex['§c5cfL0ONqkDH'/475, l='MpServer', x=-50.78, y=78.09, z=-37.72], bex['§c6bYv50WU'/478, l='MpServer', x=-51.33, y=81.29, z=1.89], bex['RiotRevoltz'/532, l='MpServer', x=-0.50, y=81.00, z=-69.50], bex['Mayu___'/531, l='MpServer', x=-69.50, y=81.00, z=1.50], uk['§e§lPlaying §f§lSKYWARS §e§lon §f§lMC.HYPIXEL.NET'/-1234, l='MpServer', x=-51.38, y=52.59, z=-5.88], bex['Equesnell'/82, l='MpServer', x=-61.50, y=81.00, z=18.50], bex['§c5Qb62mtnJEtB'/467, l='MpServer', x=-81.06, y=86.31, z=-42.38], bex['§ct3XwGfoJBNq'/468, l='MpServer', x=-84.06, y=80.59, z=-26.41], bex['§cDgZgzR2Cg'/469, l='MpServer', x=-79.50, y=85.88, z=-12.91], bex['§cHIq9Exnqm'/470, l='MpServer', x=-81.22, y=84.25, z=3.66], bex['§ciOABH9aR'/471, l='MpServer', x=-69.31, y=83.27, z=-38.77], bex['§c4rGSHr'/472, l='MpServer', x=-68.13, y=78.81, z=-29.47], bex['§c4n2cncFgxI5'/473, l='MpServer', x=-68.78, y=84.06, z=-8.66], bex['§cJBUqG2'/474, l='MpServer', x=-74.34, y=86.25, z=2.06], bex['Stelarity'/91, l='MpServer', x=62.50, y=82.16, z=-17.50], bex['§c5cfL0ONqkDH'/475, l='MpServer', x=-50.78, y=78.09, z=-37.72], bex['§cNjfqXOMTqmWj'/476, l='MpServer', x=-49.25, y=82.09, z=-29.91], up['entity.LeashKnot.name'/93, l='MpServer', x=57.50, y=82.50, z=-22.50], bex['§cFlnR4Ga'/477, l='MpServer', x=-53.63, y=87.31, z=-8.84], vs['Giant'/94, l='MpServer', x=58.09, y=86.59, z=-23.47], bex['§c6bYv50WU'/478, l='MpServer', x=-51.33, y=81.29, z=1.89], tk['Bat'/95, l='MpServer', x=61.00, y=94.59, z=-21.47], bex['§cTeNa73hVRp'/479, l='MpServer', x=-41.50, y=78.66, z=-38.88], bex['Jus2Kiwiii'/96, l='MpServer', x=70.50, y=81.00, z=-0.69], bex['§cGdmBzxx5ZH'/480, l='MpServer', x=-42.18, y=83.17, z=-29.11], bex['§cP2EjONtgy8a'/481, l='MpServer', x=-42.97, y=80.58, z=-9.71], bex['Pick1ez'/98, l='MpServer', x=-19.69, y=82.06, z=62.31], bex['§cV7YXgi3cu4JAO'/482, l='MpServer', x=-40.02, y=82.72, z=1.13], bex['NoHaxJustMineman'/99, l='MpServer', x=1.69, y=81.00, z=70.69], bex['sweet_bacon1202'/100, l='MpServer', x=20.34, y=81.00, z=-61.50], bex['harunoki86'/104, l='MpServer', x=62.31, y=81.94, z=20.69], bex['Zipboing'/106, l='MpServer', x=-17.69, y=81.00, z=-61.69], bex['HANCRAFT'/107, l='MpServer', x=18.50, y=81.00, z=62.50], up['entity.LeashKnot.name'/110, l='MpServer', x=-22.50, y=82.50, z=-56.50], vs['Giant'/111, l='MpServer', x=-23.47, y=86.59, z=-58.09], tk['Bat'/112, l='MpServer', x=-25.47, y=94.59, z=-55.22], bex['rumppork'/114, l='MpServer', x=-61.31, y=93.09, z=-19.47]]
	Retry entities: 0 total; []
	Server brand: BungeeCord (Hypixel) <- vanilla
	Server type: Non-integrated multiplayer server
Stacktrace:
	at bdb.a(SourceFile:309)
	at ave.b(SourceFile:2311)
	at ave.a(SourceFile:334)
	at net.minecraft.client.main.Main.main(SourceFile:124)

-- System Details --
Details:
	Minecraft Version: 1.8.9
	Operating System: Windows 10 (amd64) version 10.0
	Java Version: 1.8.0_51, Oracle Corporation
	Java VM Version: Java HotSpot(TM) 64-Bit Server VM (mixed mode), Oracle Corporation
	Memory: 515900328 bytes (492 MB) / 905969664 bytes (864 MB) up to 2147483648 bytes (2048 MB)
	JVM Flags: 8 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xmx2G -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M
	IntCache: cache: 0, tcache: 0, allocated: 13, tallocated: 95
	Launched Version: 1.8.9
	LWJGL: 2.9.4
	OpenGL: GeForce GTX 960/PCIe/SSE2 GL version 4.6.0 NVIDIA 432.00, NVIDIA Corporation
	GL Caps: Using GL 1.3 multitexturing.
Using GL 1.3 texture combiners.
Using framebuffer objects because OpenGL 3.0 is supported and separate blending is supported.
Shaders are available because OpenGL 2.1 is supported.
VBOs are available because OpenGL 1.5 is supported.

	Using VBOs: No
	Is Modded: Probably not. Jar signature remains and client brand is untouched.
	Type: Client (map_client.txt)
	Resource Packs: §b§l1.14 §r§bdefault textures.zip
	Current Language: English (US)
	Profiler Position: N/A (disabled)
	CPU: 4x Intel(R) Core(TM) i5-4590 CPU @ 3.30GHz
