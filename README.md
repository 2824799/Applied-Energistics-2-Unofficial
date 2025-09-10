无限频道，爽！

ME-IO端口会坏档，好像原版就有问题，换原版也没用(/(ㄒoㄒ)/~~)

传个报错信息，不知道有没有大佬能看看：

###
java.lang.VerifyError: get long/double overflows locals
Exception Details:
  Location:
    appeng/tile/storage/TileIOPort.tickingRequest(Lappeng/api/networking/IGridNode;I)Lappeng/api/networking/ticking/TickRateModulation; @57: lload
  Reason:
    Local index 6 is invalid
  Bytecode:
    0000000: 2ab6 0050 b601 cc9a 0007 b201 d2b0 2ab4
    0000010: 0063 b200 69b6 0162 c000 6b4e 2db2 0165
    0000020: a600 0e2a b400 949a 0007 b201 d2b0 2a03
    0000030: b500 9414 01d3 3704 2a16 06b8 01da 3706
    0000040: 2ab2 01dd b601 5eaa 0000 0037 0000 0001
    0000050: 0000 0003 0000 0019 0000 0024 0000 002f
    0000060: 1604 1401 de69 3704 a700 1616 0414 01e0
    0000070: 6937 04a7 000b 1604 1401 e269 3704 2ab2
    0000080: 01e6 b601 5eaa 0000 0000 0039 0000 0001
    0000090: 0000 0003 0000 001b 0000 0026 0000 0031
    00000a0: 1604 1401 e769 3704 a700 1616 0414 01e9
    00000b0: 6937 04a7 000b 1604 1401 eb69 3704 2ab2
    00000c0: 01ef b601 5eaa 0000 0000 0039 0000 0001
    00000d0: 0000 0003 0000 001b 0000 0026 0000 0031
    00000e0: 1604 1401 f069 3704 a700 1616 0414 01f2
    00000f0: 6937 04a7 000b 1604 1401 f469 3704 1604
    0000100: 3708 2ab6 0050 b601 f9b9 01ff 0100 3a0a
    0000110: 2ab6 0050 b601 f9b9 0202 0100 3a0b 2ab6
    0000120: 0050 b602 063a 0c03 360d 150d 1006 a201
    0000130: 8c2a b400 8b15 0db6 0184 3a0e 190e c601
    0000140: 762a b400 63b2 0076 b601 62b2 020f a500
    0000150: 262a b400 4c15 0d2e 04a0 001b 2ab4 004c
    0000160: 150d 2a15 0db7 0213 9a00 0704 a700 0403
    0000170: 4fa7 0143 1604 0994 9e01 382a 190e b202
    0000180: 1bb7 021f 3a0f 2a19 0eb2 0222 b702 1f3a
    0000190: 102a b400 63b2 007f b601 62b2 0084 a600
    00001a0: 3619 0fc6 0014 2a19 0c19 0f19 0a16 04b2
    00001b0: 021b b702 2637 0419 10c6 004b 2a19 0c19
    00001c0: 1019 0b16 0414 0027 69b2 0222 b702 2637
    00001d0: 04a7 0033 190f c600 142a 190c 190a 190f
    00001e0: 1604 b202 1bb7 0226 3704 1910 c600 182a
    00001f0: 190c 190b 1910 1604 1400 2769 b202 22b7
    0000200: 0226 3704 1604 0994 9e00 a42a 190f 1910
    0000210: 1604 1608 9499 0007 04a7 0004 03b7 022a
    0000220: 9900 272a b400 4c15 0d2a 150d b702 139a
    0000230: 0007 04a7 0004 034f 2ab4 004c 150d 2e04
    0000240: a000 6cb2 01d2 b02a b400 63b2 0076 b601
    0000250: 62c0 0078 b202 0fa5 0055 150d 0460 3611
    0000260: 1511 1006 a200 482a b400 4c15 112e 04a0
    0000270: 0037 2ab4 008b 150d b601 843a 1219 0ec6
    0000280: 0027 2ab4 004c 1511 2a15 11b7 0213 9a00
    0000290: 0704 a700 0403 4f2a b400 4c15 112e 04a0
    00002a0: 000d b201 d2b0 8411 01a7 ffb7 b202 2db0
    00002b0: b202 2db0 840d 01a7 fe73 a700 093a 0ab2
    00002c0: 01d2 b0b2 0230 b0                      
  Exception Handler Table:
    bci [258, 582] => handler: 701
    bci [583, 677] => handler: 701
    bci [678, 687] => handler: 701
    bci [688, 691] => handler: 701
    bci [692, 698] => handler: 701
  Stackmap Table:
    same_frame(@14)
    append_frame(@46,Object[#107])
    append_frame(@96,Long)
    same_frame(@107)
    same_frame(@118)
    same_frame(@126)
    same_frame(@160)
    same_frame(@171)
    same_frame(@182)
    same_frame(@190)
    same_frame(@224)
    same_frame(@235)
    same_frame(@246)
    same_frame(@254)
    full_frame(@298,{Object[#2],Object[#520],Integer,Object[#107],Long,Top,Top,Long,Object[#522],Object[#522],Object[#524],Integer},{})
    full_frame(@367,{Object[#2],Object[#520],Integer,Object[#107],Long,Top,Top,Long,Object[#522],Object[#522],Object[#524],Integer,Object[#533]},{Object[#424],Integer})
    full_frame(@368,{Object[#2],Object[#520],Integer,Object[#107],Long,Top,Top,Long,Object[#522],Object[#522],Object[#524],Integer,Object[#533]},{Object[#424],Integer,Integer})
    same_frame(@372)
    append_frame(@439,Object[#522],Object[#522])
    same_frame(@468)
    same_frame(@490)
    same_frame(@516)
    full_frame(@540,{Object[#2],Object[#520],Integer,Object[#107],Long,Top,Top,Long,Object[#522],Object[#522],Object[#524],Integer,Object[#533],Object[#522],Object[#522]},{Object[#2],Object[#522],Object[#522]})
    full_frame(@541,{Object[#2],Object[#520],Integer,Object[#107],Long,Top,Top,Long,Object[#522],Object[#522],Object[#524],Integer,Object[#533],Object[#522],Object[#522]},{Object[#2],Object[#522],Object[#522],Integer})
    full_frame(@566,{Object[#2],Object[#520],Integer,Object[#107],Long,Top,Top,Long,Object[#522],Object[#522],Object[#524],Integer,Object[#533],Object[#522],Object[#522]},{Object[#424],Integer})
    full_frame(@567,{Object[#2],Object[#520],Integer,Object[#107],Long,Top,Top,Long,Object[#522],Object[#522],Object[#524],Integer,Object[#533],Object[#522],Object[#522]},{Object[#424],Integer,Integer})
    same_frame(@583)
    append_frame(@608,Integer)
    full_frame(@661,{Object[#2],Object[#520],Integer,Object[#107],Long,Top,Top,Long,Object[#522],Object[#522],Object[#524],Integer,Object[#533],Object[#522],Object[#522],Integer,Object[#533]},{Object[#424],Integer})
    full_frame(@662,{Object[#2],Object[#520],Integer,Object[#107],Long,Top,Top,Long,Object[#522],Object[#522],Object[#524],Integer,Object[#533],Object[#522],Object[#522],Integer,Object[#533]},{Object[#424],Integer,Integer})
    chop_frame(@678,1)
    chop_frame(@684,1)
    chop_frame(@688,2)
    chop_frame(@692,1)
    full_frame(@698,{Object[#2],Object[#520],Integer,Object[#107],Long,Top,Top,Long},{})
    same_locals_1_stack_item_frame(@701,Object[#283])
    same_frame(@707)

    at java.lang.Class.getDeclaredConstructors0(Native Method)
    at java.lang.Class.privateGetDeclaredConstructors(Unknown Source)
    at java.lang.Class.getConstructor0(Unknown Source)
    at java.lang.Class.newInstance(Unknown Source)
    at appeng.block.AEBaseTileBlock.createNewTileEntity(AEBaseTileBlock.java:120)
    at net.minecraft.block.Block.createTileEntity(Block.java:1446)
    at net.minecraft.world.chunk.Chunk.func_150806_e(Chunk.java:850)
    at net.minecraft.world.World.getTileEntity(World.java:2540)
    at appeng.block.AEBaseTileBlock.getTileEntity(AEBaseTileBlock.java:108)
    at appeng.block.AEBaseTileBlock.getCustomCollision(AEBaseTileBlock.java:320)
    at appeng.block.AEBaseBlock.collisionRayTrace(AEBaseBlock.java:289)
    at net.minecraft.world.World.func_147447_a(World.java:1221)
    at net.minecraft.world.World.rayTraceBlocks(World.java:1029)
    at mcp.mobius.waila.overlay.RayTracing.rayTrace(RayTracing.java:84)
    at mcp.mobius.waila.overlay.RayTracing.fire(RayTracing.java:48)
    at mcp.mobius.waila.overlay.WailaTickHandler.tickClient(WailaTickHandler.java:50)
    at cpw.mods.fml.common.eventhandler.ASMEventHandler_1316_WailaTickHandler_tickClient_ClientTickEvent.invoke(.dynamic)
    at cpw.mods.fml.common.eventhandler.ASMEventHandler.invoke(ASMEventHandler.java:54)
    at cpw.mods.fml.common.eventhandler.EventBus.post(EventBus.java:140)
    at cpw.mods.fml.common.FMLCommonHandler.onPostClientTick(FMLCommonHandler.java:330)
    at net.minecraft.client.Minecraft.runTick(Minecraft.java:2064)
    at net.minecraft.client.Minecraft.runGameLoop(Minecraft.java:973)
    at net.minecraft.client.Minecraft.run(Minecraft.java:7110)
    at net.minecraft.client.main.Main.main(SourceFile:148)
    at jdk.internal.reflect.DirectMethodHandleAccessor.invoke(Unknown Source)
    at java.lang.reflect.Method.invoke(Unknown Source)
    at net.minecraft.launchwrapper.Launch.rfb$realLaunch(Launch.java:250)
    at net.minecraft.launchwrapper.Launch.launch(Launch.java:35)
    at net.minecraft.launchwrapper.Launch.main(Launch.java:60)
    at jdk.internal.reflect.DirectMethodHandleAccessor.invoke(Unknown Source)
    at java.lang.reflect.Method.invoke(Unknown Source)
    at com.gtnewhorizons.retrofuturabootstrap.Main.main(Main.java:207)
    at org.prismlauncher.launcher.impl.StandardLauncher.launch(StandardLauncher.java:105)
    at org.prismlauncher.EntryPoint.listen(EntryPoint.java:129)
    at org.prismlauncher.EntryPoint.main(EntryPoint.java:70)
###
