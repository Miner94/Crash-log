# Crash-log Minecraft 1.10 with minefactory reloaded 
---- Minecraft Crash Report ----

WARNING: coremods are present:
  BookshelfLoadingPlugin (Bookshelf-1.10.2-1.4.4.347.jar)
  LoadingPlugin (RandomThings-MC1.10.2-3.7.7.jar)
  LoadingPlugin (ResourceLoader-MC1.9.4-1.5.1.jar)
  Brandon's Core (BrandonsCore-1.10.2-2.1.7.102-universal.jar)
  EnderCorePlugin (EnderCore-1.10.2-0.4.1.66-beta.jar)
  CCLCorePlugin (CodeChickenLib-1.10.2-2.5.8.255-universal.jar)
  TransformerLoader (OpenComputers-MC1.10.2-1.6.2.7.jar)
  CoFH Loading Plugin (CoFHCore-1.10.2-4.1.4.7-universal (1).jar)
  SFRCore (SolarFluxReborn_1.10.2-2.16r.jar)
  LoadingPlugin (Quark-r1.1-70.jar)
  NEICorePlugin (NotEnoughItems-1.10.2-2.1.3.220-universal.jar)
  CXLibraryCore (cxlibrary-1.10.2-1.2.3.jar)
  ShetiPhian-ASM (shetiphiancore-1.10.0-3.3.6.jar)
  RebornCoreASM (RebornCore-1.10.2-2.13.5.136-universal.jar)
  AppEngCore (appliedenergistics2-rv4-alpha-11.jar)
  FMLPlugin (InventoryTweaks-1.61-58.jar)
  IvToolkit (IvToolkit-1.3.3-1.10.jar)
  IC2core (industrialcraft-2-2.6.188-ex110.jar)
  CorePlugin (MrTJPCore-1.10.2-2.0.0.17-universal.jar)
Contact their authors BEFORE contacting forge

// Daisy, daisy...

Time: 6/16/17 6:27 PM
Description: There was a severe problem during mod loading that has caused the game to fail

net.minecraftforge.fml.common.LoaderExceptionModCrash: Caught exception from MineFactory Reloaded (minefactoryreloaded)
Caused by: java.lang.NoSuchMethodError: powercrystals.minefactoryreloaded.block.fluid.BlockFactoryFluid.setHardness(F)Lnet/minecraft/block/Block;
	at powercrystals.minefactoryreloaded.block.fluid.BlockFactoryFluid.<init>(BlockFactoryFluid.java:64)
	at powercrystals.minefactoryreloaded.block.fluid.BlockFactoryFluid.<init>(BlockFactoryFluid.java:58)
	at powercrystals.minefactoryreloaded.setup.MFRFluids.preInit(MFRFluids.java:78)
	at powercrystals.minefactoryreloaded.MineFactoryReloadedCore.preInit(MineFactoryReloadedCore.java:114)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source)
	at java.lang.reflect.Method.invoke(Unknown Source)
	at net.minecraftforge.fml.common.FMLModContainer.handleModStateEvent(FMLModContainer.java:616)
	at sun.reflect.GeneratedMethodAccessor3.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source)
	at java.lang.reflect.Method.invoke(Unknown Source)
	at com.google.common.eventbus.EventSubscriber.handleEvent(EventSubscriber.java:74)
	at com.google.common.eventbus.SynchronizedEventSubscriber.handleEvent(SynchronizedEventSubscriber.java:47)
	at com.google.common.eventbus.EventBus.dispatch(EventBus.java:322)
	at com.google.common.eventbus.EventBus.dispatchQueuedEvents(EventBus.java:304)
	at com.google.common.eventbus.EventBus.post(EventBus.java:275)
	at net.minecraftforge.fml.common.LoadController.sendEventToModContainer(LoadController.java:243)
	at net.minecraftforge.fml.common.LoadController.propogateStateMessage(LoadController.java:221)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source)
	at java.lang.reflect.Method.invoke(Unknown Source)
	at com.google.common.eventbus.EventSubscriber.handleEvent(EventSubscriber.java:74)
	at com.google.common.eventbus.SynchronizedEventSubscriber.handleEvent(SynchronizedEventSubscriber.java:47)
	at com.google.common.eventbus.EventBus.dispatch(EventBus.java:322)
	at com.google.common.eventbus.EventBus.dispatchQueuedEvents(EventBus.java:304)
	at com.google.common.eventbus.EventBus.post(EventBus.java:275)
	at net.minecraftforge.fml.common.LoadController.distributeStateMessage(LoadController.java:145)
	at net.minecraftforge.fml.common.Loader.preinitializeMods(Loader.java:624)
	at net.minecraftforge.fml.client.FMLClientHandler.beginMinecraftLoading(FMLClientHandler.java:259)
	at net.minecraft.client.Minecraft.func_71384_a(Minecraft.java:439)
	at net.minecraft.client.Minecraft.func_99999_d(Minecraft.java:351)
	at net.minecraft.client.main.Main.main(SourceFile:124)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source)
	at java.lang.reflect.Method.invoke(Unknown Source)
	at net.minecraft.launchwrapper.Launch.launch(Launch.java:135)
	at net.minecraft.launchwrapper.Launch.main(Launch.java:28)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(Unknown Source)
	at java.lang.reflect.Method.invoke(Unknown Source)
	at org.multimc.onesix.OneSixLauncher.launchWithMainClass(OneSixLauncher.java:310)
	at org.multimc.onesix.OneSixLauncher.launch(OneSixLauncher.java:394)
	at org.multimc.EntryPoint.listen(EntryPoint.java:170)
	at org.multimc.EntryPoint.main(EntryPoint.java:54)


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- System Details --
Details:
	Minecraft Version: 1.10.2
	Operating System: Windows 8.1 (amd64) version 6.3
	Java Version: 1.8.0_131, Oracle Corporation
	Java VM Version: Java HotSpot(TM) 64-Bit Server VM (mixed mode), Oracle Corporation
	Memory: 560295960 bytes (534 MB) / 1630535680 bytes (1555 MB) up to 4260102144 bytes (4062 MB)
	JVM Flags: 9 total; -XX:+DisableExplicitGC -XX:+UseConcMarkSweepGC -XX:MaxGCPauseMillis=40 -XX:CMSInitiatingOccupancyFraction=70 -XX:+CMSScavengeBeforeRemark -XX:+AggressiveOpts -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xms1024m -Xmx4096m
	IntCache: cache: 0, tcache: 0, allocated: 0, tallocated: 0
	FML: MCP 9.32 Powered by Forge 12.18.3.2316 Optifine OptiFine_1.10.2_HD_U_D8 146 mods loaded, 146 mods active
	States: 'U' = Unloaded 'L' = Loaded 'C' = Constructed 'H' = Pre-initialized 'I' = Initialized 'J' = Post-initialized 'A' = Available 'D' = Disabled 'E' = Errored
	UCH	mcp{9.19} [Minecraft Coder Pack] (minecraft.jar) 
	UCH	FML{8.0.99.99} [Forge Mod Loader] (forge-1.10.2-12.18.3.2316-universal.jar) 
	UCH	Forge{12.18.3.2316} [Minecraft Forge] (forge-1.10.2-12.18.3.2316-universal.jar) 
	UCH	appliedenergistics2-core{rv4-alpha-11} [Applied Energistics 2 Core] (minecraft.jar) 
	UCH	ivtoolkit{1.3.3-1.10} [IvToolkit] (minecraft.jar) 
	UCH	NotEnoughItems{2.1.3.220} [Not Enough Items] (NotEnoughItems-1.10.2-2.1.3.220-universal.jar) 
	UCH	OpenComputers|Core{1.6.2.7} [OpenComputers (Core)] (minecraft.jar) 
	UCH	<CoFH ASM>{000} [CoFH ASM] (minecraft.jar) 
	UCH	ccl-entityhook{1.0} [ccl-entityhook] (CodeChickenLib-1.10.2-2.5.8.255-universal.jar) 
	UCH	uncraftingTable{1.6-pre1} [Uncrafting Table] ([1.9.4]UncraftingTable-1.6-pre1.jar) 
	UCH	cofhcore{4.1.4} [CoFH Core] (CoFHCore-1.10.2-4.1.4.7-universal (1).jar) 
	UCH	actuallyadditions{1.10.2-r105} [Actually Additions] (ActuallyAdditions-1.10.2-r105.jar) 
	UCH	Baubles{1.3.9} [Baubles] (Baubles-1.10.2-1.3.9.jar) 
	UCH	JEI{3.14.7.419} [Just Enough Items] (jei_1.10.2-3.14.7.419.jar) 
	UCH	extrautils2{1.0} [Extra Utilities 2] (extrautils2-1.10.2-1.4.3.jar) 
	UCH	flyringbaublemod{0.2.3_1.10.2-d3100bf} [AngelRing 2 Bauble] (angelRingToBauble-1.10.2-0.2.3.16+d3100bf.jar) 
	UCH	appliedenergistics2{rv4-alpha-11} [Applied Energistics 2] (appliedenergistics2-rv4-alpha-11.jar) 
	UCH	Quark{r1.1-70} [Quark] (Quark-r1.1-70.jar) 
	UCH	AutoRegLib{1.0-2} [AutoRegLib] (AutoRegLib-1.0-2.jar) 
	UCH	bdlib{1.12.4.24} [BD Lib] (bdlib-1.12.4.24-mc1.10.2.jar) 
	UCH	BetterAchievements{0.3.2.39} [Better Achievements] (BetterAchievements-1.10.2-0.3.2.39.jar) 
	UCH	betterbuilderswands{0.11.1} [Better Builder's Wands] (BetterBuildersWands-1.10.2-0.11.1.220+f8232fe.jar) 
	UCH	guideapi{@VERSION@} [Guide-API] (Guide-API-1.10.2-2.0.3-46.jar) 
	UCH	BloodMagic{1.10.2-2.1.9-78} [Blood Magic: Alchemical Wizardry] (BloodMagic-1.10.2-2.1.9-78.jar) 
	UCH	bookshelf{1.4.4.347} [Bookshelf] (Bookshelf-1.10.2-1.4.4.347.jar) 
	UCH	Botania{r1.9-341} [Botania] (Botania r1.9-341.jar) 
	UCH	CodeChickenLib{2.5.8.255} [CodeChicken Lib] (CodeChickenLib-1.10.2-2.5.8.255-universal.jar) 
	UCH	brandonscore{9.9.9} [Brandon's Core] (BrandonsCore-1.10.2-2.1.7.102-universal.jar) 
	UCH	Chameleon{1.10-2.2.2} [Chameleon] (Chameleon-1.10-2.2.2.jar) 
	UCH	chancecubes{1.10.2-3.0.1.189} [Chance Cubes] (ChanceCubes-1.10.2-3.0.1.189.jar) 
	UCH	ChestTransporter{2.5.10} [Chest Transporter] (ChestTransporter-1.10.2-2.5.10.jar) 
	UCH	CodeChickenCore{2.4.1.102} [CodeChicken Core] (CodeChickenCore-1.10.2-2.4.1.102-universal.jar) 
	UCH	cyclopscore{0.10.2} [Cyclops Core] (CyclopsCore-1.9.4-0.10.2.jar) 
	UCH	commoncapabilities{1.3.2} [CommonCapabilities] (CommonCapabilities-1.9.4-1.3.2.jar) 
	UCH	IC2{2.6.188-ex110} [IndustrialCraft 2] (industrialcraft-2-2.6.188-ex110.jar) 
	UCH	compactsolars{1.10.2-5.0.8.331} [Compact Solar Arrays] (CompactSolars-1.10.2-5.0.8.331-universal.jar) 
	UCH	cookingforblockheads{4.2.39} [Cooking for Blockheads] (CookingForBlockheads_1.10.2-4.2.39.jar) 
	UCH	crafttweakerjei{1.0.1} [CraftTweaker JEI Support] (CraftTweaker-1.10.2-3.0.25.jar) 
	UCH	MineTweaker3{3.0.25} [MineTweaker 3] (CraftTweaker-1.10.2-3.0.25.jar) 
	UCH	ctgui{1.0.0} [CT-GUI] (CraftTweaker-1.10.2-3.0.25.jar) 
	UCH	cxlibrary{1.2.3} [CXLibrary] (cxlibrary-1.10.2-1.2.3.jar) 
	UCH	cyclicmagic{1.10.24} [Cyclic] (Cyclic-1.10.2-1.10.24.jar) 
	UCH	Waila{1.7.0} [Waila] (Waila-1.7.0-B3_1.9.4.jar) 
	UCH	darkutils{1.1.7.111} [Dark Utilities] (DarkUtilities-1.10.2-1.1.7.111.jar) 
	UCH	forestry{5.2.17.368} [Forestry] (forestry_1.10.2-5.2.17.368.jar) 
	UCH	eleccore{1.7.418} [ElecCore] (ElecCore-1.10.2-1.7.418.jar) 
	UCH	EnderStorage{2.2.1.106} [EnderStorage] (EnderStorage-1.10.2-2.2.1.106-universal.jar) 
	UCH	OpenComputers{1.6.2.7} [OpenComputers] (OpenComputers-MC1.10.2-1.6.2.7.jar) 
	UCH	deepresonance{1.4.8} [DeepResonance] (deepresonance-1.1x-1.4.8.jar) 
	UCH	draconicevolution{2.0.10} [Draconic Evolution] (Draconic-Evolution-1.10.2-2.0.10.199-universal.jar) 
	UCH	drones{0.1.17} [drones] (Drones-0.1.17.jar) 
	UCH	endercore{1.10.2-0.4.1.66-beta} [EnderCore] (EnderCore-1.10.2-0.4.1.66-beta.jar) 
	UCH	EnderIO{1.10.2-3.1.192} [Ender IO] (EnderIO-1.10.2-3.1.192.jar) 
	UCH	valkyrielib{1.10.2-0.10.6} [Valkyrie Lib] (valkyrielib-1.10.2-0.10.6.jar) 
	UCH	environmentaltech{1.10.2-0.10.6b} [Environmental Tech] (environmentaltech-1.10.2-0.10.6b.jar) 
	UCH	etlunar{1.10.2-0.10.6a} [ET Lunar] (etlunar-1.10.2-0.10.6a.jar) 
	UCH	zerocore{1.10.2-0.1.0.5} [Zero CORE] (zerocore-1.10.2-0.1.0.5.jar) 
	UCH	bigreactors{1.10.2-0.4.5.28} [Extreme Reactors] (ExtremeReactors-1.10.2-0.4.5.28.jar) 
	UCH	FastLeaveDecay{1.2.3} [Fast Leave Decay] (FastLeaveDecay-MC1.10.2-1.2.3.jar) 
	UCH	sonarcore{3.2.7} [SonarCore] (SonarCore-1.10.2-3.2.7.jar) 
	UCH	fluxnetworks{1.2.3} [FluxNetworks] (FluxNetworks-1.10.2-1.2.3.jar) 
	UCH	foamfix{@VERSION@} [FoamFix] (foamfix-0.6.3-law.jar) 
	UCH	forgemultipartcbe{2.0.0.31} [Forge Multipart CBE] (ForgeMultipart-1.10.2-2.0.0.31-universal.jar) 
	UCH	microblockcbe{2.0.0.31} [Forge Microblocks] (ForgeMultipart-1.10.2-2.0.0.31-universal.jar) 
	UCH	minecraftmultipartcbe{2.0.0.31} [Minecraft Multipart Plugin] (ForgeMultipart-1.10.2-2.0.0.31-universal.jar) 
	UCH	mcmultipart{1.4.0} [MCMultiPart] (MCMultiPart-1.4.0-universal.jar) 
	UCH	ftbl{0.0.0} [FTBLib] (FTBLib-1.10.2-3.4.5.jar) 
	UCH	ftbu{0.0.0} [FTBUtilities] (FTBUtilities-1.10.2-3.4.4.jar) 
	UCH	pressure{1.3.1.22} [Pressure Pipes] (pressure-1.3.1.22-mc1.10.2.jar) 
	UCH	advgenerators{0.9.20.23} [Advanced Generators] (generators-0.9.20.23-mc1.10.2.jar) 
	UCH	gwgmcgenmod{1.4} [gmCGENmod] (gmcgenmod-mc1.10.2-v1.4.jar) 
	UCH	StorageDrawers{1.10.2-3.7.1} [Storage Drawers] (StorageDrawers-1.10.2-3.7.1.jar) 
	UCH	refinedstorage{1.2.26} [Refined Storage] (refinedstorage-1.2.26.jar) 
	UCH	growablecells{1.0.2} [Growable Cells] (Growable Cells-1.10.2-1.0.2.jar) 
	UCH	hammercore{1.4.8} [Hammer Core] (HammerCore_1.10.2-1.4.8.jar) 
	UCH	mantle{1.10.2-1.1.5.205} [Mantle] (Mantle-1.10.2-1.1.5.jar) 
	UCH	tconstruct{1.10.2-2.6.3.500} [Tinkers' Construct] (TConstruct-1.10.2-2.6.3.jar) 
	UCH	theoneprobe{1.4.6} [The One Probe] (theoneprobe-1.1x-1.4.6.jar) 
	UCH	immersiveengineering{0.10-58} [Immersive Engineering] (ImmersiveEngineering-0.10-58.jar) 
	UCH	industrialwires{1.4-9} [Industrial Wires] (IndustrialWires-1.4-9.jar) 
	UCH	inventorytweaks{1.61-58-a1fd884} [Inventory Tweaks] (InventoryTweaks-1.61-58.jar) 
	UCH	ironbackpacks{1.10.2-2.2.25} [Iron Backpacks] (IronBackpacks-1.10.2-2.2.25.jar) 
	UCH	ironchest{1.10.2-7.0.11.797} [Iron Chest] (ironchest-1.10.2-7.0.11.797.jar) 
	UCH	jeibees{0.9.0.4} [JEI Bees] (jeibees-0.9.0.4-mc1.10.2.jar) 
	UCH	journeymap{1.10.2-5.4.6} [JourneyMap] (journeymap-1.10.2-5.4.6.jar) 
	UCH	jeresources{0.5.9.3} [Just Enough Resources] (JustEnoughResources-1.10.2-0.5.9.3.jar) 
	UCH	lightningcraft{2.7.2} [LightningCraft] (lightningcraft-2.7.2-[1.10.2].jar) 
	UCH	llor{1.1.1-mc[1.9-1.11]} [Light Level Overlay Reloaded] (LLOverlayReloaded-1.1.1-mc[1.9-1.11].jar) 
	UCH	Mekanism{9.2.2} [Mekanism] (Mekanism-1.10.2-9.2.2.301.jar) 
	UCH	MekanismGenerators{9.2.2} [MekanismGenerators] (MekanismGenerators-1.10.2-9.2.2.301.jar) 
	UCE	minefactoryreloaded{2.9.0B1} [MineFactory Reloaded] (MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar) 
	UCH	MineFactoryReloaded|CompatVanilla{2.9.0B1} [MFR Compat: Vanilla] (MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar) 
	UCH	ProjectE{1.10.2-PE1.2.0} [ProjectE] (ProjectE-1.10.2-PE1.2.0.jar) 
	UCH	moartinkers{0.4.0} [Moar Tinkers] (moartinkers-0.4.0.jar) 
	UCH	mtlib{@VERSION@} [MTLib] (MTLib-1.0.2.jar) 
	UCH	modtweaker{2.0.11} [Mod Tweaker] (ModTweaker2-2.0.11.jar) 
	UCH	MoreFurnaces{1.8.4} [More Furnaces] (MoreFurnaces-1.10.2-1.8.4.jar) 
	UCH	mousetweaks{2.8} [Mouse Tweaks] (MouseTweaks-2.8-mc1.10.2.jar) 
	UCH	MrTJPCoreMod{2.0.0.17} [MrTJPCore] (MrTJPCore-1.10.2-2.0.0.17-universal.jar) 
	UCH	mysticalagriculture{1.5.4} [Mystical Agriculture] (mysticalagriculture[1.10.2]-1.5.4.jar) 
	UCH	natura{1.10.2-4.1.0.34} [Natura] (natura-1.10.2-4.1.0.34.jar) 
	UCH	nethercore{1.10.2-2.0.3} [Nether Core] (nethercore-1.10.2-2.0.3.jar) 
	UCH	recipehandler{0.6} [NoMoreRecipeConflict] (NoMoreRecipeConflict-0.6(1.10.2).jar) 
	UCH	notenoughwands{1.4.0} [Not Enough Wands] (notenoughwands-1.10-1.4.0.jar) 
	UCH	fodc{1.9.1} [Ore Dictionary Converter] (OreDictionaryConverter-1.9.1.jar) 
	UCH	p455w0rdslib{1.0.3} [p455w0rd's Library] (p455w0rdslib-1.9.4-1.0.3.jar) 
	UCH	harvestcraft{1.9.4-1.10.2g} [Pam's HarvestCraft] (Pam's HarvestCraft 1.9.4-1.10.2h.jar) 
	UCH	projectred-core{4.8.2.41} [ProjectRed Core] (ProjectRed-1.10.2-4.8.2.41-Base.jar) 
	UCH	projectred-integration{4.8.2.41} [ProjectRed integration] (ProjectRed-1.10.2-4.8.2.41-integration.jar) 
	UCH	projectred-transmission{4.8.2.41} [ProjectRed Transmission] (ProjectRed-1.10.2-4.8.2.41-integration.jar) 
	UCH	projectred-expansion{4.8.2.41} [ProjectRed Expansion] (ProjectRed-1.10.2-4.8.2.41-mechanical.jar) 
	UCH	projectred-transportation{4.8.2.41} [ProjectRed Transportation] (ProjectRed-1.10.2-4.8.2.41-mechanical.jar) 
	UCH	projectred-exploration{4.8.2.41} [ProjectRed Exploration] (ProjectRed-1.10.2-4.8.2.41-world.jar) 
	UCH	railcraft{10.1.1} [Railcraft] (Railcraft_1.10.2-10.1.1.jar) 
	UCH	randomthings{3.7.7} [Random Things] (RandomThings-MC1.10.2-3.7.7.jar) 
	UCH	rangedpumps{0.3} [Ranged Pumps] (rangedpumps-0.3.jar) 
	UCH	reborncore{2.13.5.136} [RebornCore] (RebornCore-1.10.2-2.13.5.136-universal.jar) 
	UCH	reborncore-mcmultipart{2.13.5.136} [reborncore-MCMultiPart] (RebornCore-1.10.2-2.13.5.136-universal.jar) 
	UCH	rebornstorage{1.0.0} [RebornStorage] (RebornStorage-1.10.2-1.0.1.27.jar) 
	UCH	reccomplex{1.3.2-1.10} [Recurrent Complex] (RecurrentComplex-1.3.2-1.10.jar) 
	UCH	xreliquary{1.10.2-1.3.3.585} [Reliquary] (Reliquary-1.10.2-1.3.3.585.jar) 
	UCH	ResourceLoader{1.5.1} [Resource Loader] (ResourceLoader-MC1.9.4-1.5.1.jar) 
	UCH	rftools{6.00} [RFTools] (rftools-1.1x-6.00.jar) 
	UCH	rftoolsdim{4.55} [RFTools Dimensions] (rftoolsdim-1.1x-4.55.jar) 
	UCH	roguelike{1.5.9} [Roguelike Dungeons] (RoguelikeDungeons-1.10.2-1.5.9.jar) 
	UCH	shetiphiancore{3.3.6} [ShetiPhian-Core] (shetiphiancore-1.10.0-3.3.6.jar) 
	UCH	simplegenerators{1.10.2-0.10.6a} [Simple Generators] (simplegenerators-1.10.2-0.10.6a.jar) 
	UCH	simplyjetpacks{2.0.3.26} [Simply Jetpacks 2] (SimplyJetpacks2-1.10.2-2.0.3.26.jar) 
	UCH	solarfluxreborn{2.16r} [Solar Flux Reborn] (SolarFluxReborn_1.10.2-2.16r.jar) 
	UCH	soulshardstow{1.10.2-2.6.7-48} [Soul Shards - The Old Ways] (SoulShards-TOW-1.10.2-2.6.7-48.jar) 
	UCH	StevesFactoryManager{1.0.12} [Steve's Factory Manager] (StevesFactoryManager-1.10.2-1.0.12.jar) 
	UCH	thermalfoundation{2.0.5} [Thermal Foundation] (ThermalFoundation-1.10.2-2.0.5.81-universal.jar) 
	UCH	thermalexpansion{5.0.4} [Thermal Expansion] (ThermalExpansion-1.10.2-5.0.4.90-universal.jar) 
	UCH	TinkersAddons{1.0.5} [Tinkers' Addons] (Tinkers' Addons-1.10.x-1.0.5.jar) 
	UCH	tinkertoolleveling{1.10.2-1.0.1.DEV.f5def58} [Tinkers Tool Leveling] (TinkerToolLeveling-1.10.2-1.0.1.jar) 
	UCH	tp{1.2.0-Hotfix} [Tiny Progressions] (tinyprogressions-1.10.2-1.2.0-Hotfix.jar) 
	UCH	Torcherino{4.2s} [Torcherino] (Torcherino-4.2s.jar) 
	UCH	VeinMiner{0.35.3_1.9-a46c1b0} [Vein Miner] (VeinMiner-1.9-0.35.3.595+a46c1b0.jar) 
	UCH	VeinMinerModSupport{0.35.3_1.9-a46c1b0} [Mod Support] (VeinMiner-1.9-0.35.3.595+a46c1b0.jar) 
	UCH	WailaHarvestability{1.1.9} [Waila Harvestability] (WailaHarvestability-mc1.10.2-1.1.9.jar) 
	UCH	wanionlib{1.10.2-1.3} [WanionLib] (WanionLib-1.10.2-1.3.jar) 
	UCH	icse{1.1.0.0} [I Can See Everything] (Wawla-1.10.2-2.3.2.215.jar) 
	UCH	wawla{2.3.2.215} [What Are We Looking At] (Wawla-1.10.2-2.3.2.215.jar) 
	UCH	wcg{1.0.0} [Wireless Crafting Grid] (WirelessCraftingGrid-1.10.2-1.0.0.jar) 
	UCH	Woot{1.10.2-1.2.4} [Woot] (woot-1.10.2-1.2.4.jar) 
	UCH	unidict{1.10.2-2.8} [UniDict] (UniDict-1.10.2-2.8.jar) 
	Loaded coremods (and transformers): 
BookshelfLoadingPlugin (Bookshelf-1.10.2-1.4.4.347.jar)
  net.darkhax.bookshelf.asm.BookshelfTransformerManager
LoadingPlugin (RandomThings-MC1.10.2-3.7.7.jar)
  lumien.randomthings.asm.ClassTransformer
LoadingPlugin (ResourceLoader-MC1.9.4-1.5.1.jar)
  lumien.resourceloader.asm.ClassTransformer
Brandon's Core (BrandonsCore-1.10.2-2.1.7.102-universal.jar)
  com.brandon3055.brandonscore.asm.ClassTransformer
EnderCorePlugin (EnderCore-1.10.2-0.4.1.66-beta.jar)
  com.enderio.core.common.transform.EnderCoreTransformer
CCLCorePlugin (CodeChickenLib-1.10.2-2.5.8.255-universal.jar)
  codechicken.lib.asm.ClassHeirachyManager
  codechicken.lib.asm.CCL_ASMTransformer
TransformerLoader (OpenComputers-MC1.10.2-1.6.2.7.jar)
  li.cil.oc.common.asm.ClassTransformer
CoFH Loading Plugin (CoFHCore-1.10.2-4.1.4.7-universal (1).jar)
  cofh.asm.CoFHClassTransformer
  cofh.asm.repack.codechicken.lib.asm.ClassHierarchyManager
SFRCore (SolarFluxReborn_1.10.2-2.16r.jar)
  com.mrdimka.solarfluxreborn.core.SFRSerializedTransformer
LoadingPlugin (Quark-r1.1-70.jar)
  vazkii.quark.base.asm.ClassTransformer
NEICorePlugin (NotEnoughItems-1.10.2-2.1.3.220-universal.jar)
  codechicken.nei.asm.NEITransformer
CXLibraryCore (cxlibrary-1.10.2-1.2.3.jar)
  cubex2.cxlibrary.CoreModTransformer
ShetiPhian-ASM (shetiphiancore-1.10.0-3.3.6.jar)
  shetiphian.core.asm.ClassTransformer
RebornCoreASM (RebornCore-1.10.2-2.13.5.136-universal.jar)
  reborncore.mixin.transformer.MixinTransformer
AppEngCore (appliedenergistics2-rv4-alpha-11.jar)
  appeng.coremod.transformer.ASMIntegration
FMLPlugin (InventoryTweaks-1.61-58.jar)
  invtweaks.forge.asm.ContainerTransformer
IvToolkit (IvToolkit-1.3.3-1.10.jar)
  
IC2core (industrialcraft-2-2.6.188-ex110.jar)
  
CorePlugin (MrTJPCore-1.10.2-2.0.0.17-universal.jar)
  
	GL info: ' Vendor: 'ATI Technologies Inc.' Version: '4.2.12420 Compatibility Profile Context 13.151.0.0' Renderer: 'AMD Radeon HD 8650G'
	AE2 Version: alpha rv4-alpha-11 for Forge 12.18.3.2185
	Pulsar/tconstruct loaded Pulses: 
		- TinkerCommons (Enabled/Forced)
		- TinkerWorld (Enabled/Not Forced)
		- TinkerTools (Enabled/Not Forced)
		- TinkerHarvestTools (Enabled/Forced)
		- TinkerMeleeWeapons (Enabled/Forced)
		- TinkerRangedWeapons (Enabled/Forced)
		- TinkerModifiers (Enabled/Forced)
		- TinkerSmeltery (Enabled/Not Forced)
		- TinkerGadgets (Enabled/Not Forced)
		- TinkerOredict (Enabled/Forced)
		- TinkerIntegration (Enabled/Forced)
		- TinkerFluids (Enabled/Forced)
		- TinkerMaterials (Enabled/Forced)
		- TinkerModelRegister (Enabled/Forced)
		- WailaIntegration (Enabled/Not Forced)
		- theoneprobeIntegration (Enabled/Not Forced)

	minefactoryreloaded: -[1.10.2]2.9.0B1-215
	Pulsar/natura loaded Pulses: 
		- NaturaCommons (Enabled/Forced)
		- NaturaOverworld (Enabled/Not Forced)
		- NaturaNether (Enabled/Not Forced)
		- NaturaTools (Enabled/Not Forced)
		- NaturaEntities (Enabled/Not Forced)
		- NaturaOredict (Enabled/Forced)
		- NaturaWorld (Enabled/Not Forced)
		- WailaIntegration (Enabled/Not Forced)

	NotEnoughItems Invalid Fingerprint Reports: 
	List of loaded APIs: 
		* actuallyadditionsapi (29) from ActuallyAdditions-1.10.2-r105.jar
		* appliedenergistics2|API (rv4) from appliedenergistics2-rv4-alpha-11.jar
		* Baubles|API (1.3.1.3) from Baubles-1.10.2-1.3.9.jar
		* BetterAchievements|API (0.3.2.39) from BetterAchievements-1.10.2-0.3.2.39.jar
		* bigreactors|API (4.0.1) from ExtremeReactors-1.10.2-0.4.5.28.jar
		* BloodMagic|API (@VERSION@) from BloodMagic-1.10.2-2.1.9-78.jar
		* BotaniaAPI (85) from Botania r1.9-341.jar
		* BuildCraftAPI|blocks (1.0) from MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar
		* BuildCraftAPI|blueprints (1.5) from MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar
		* BuildCraftAPI|boards (2.0) from MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar
		* BuildCraftAPI|core (2.2) from MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar
		* BuildCraftAPI|crops (1.1) from MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar
		* BuildCraftAPI|enums (1.0) from MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar
		* BuildCraftAPI|events (2.0) from MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar
		* BuildCraftAPI|facades (1.1) from MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar
		* BuildCraftAPI|filler (4.0) from MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar
		* BuildCraftAPI|fuels (2.0) from MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar
		* BuildCraftAPI|gates (4.1) from MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar
		* BuildCraftAPI|items (1.1) from MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar
		* BuildCraftAPI|library (2.0) from MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar
		* BuildCraftAPI|lists (1.0) from MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar
		* BuildCraftAPI|power (1.3) from MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar
		* BuildCraftAPI|recipes (3.0) from MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar
		* BuildCraftAPI|robotics (3.0) from MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar
		* BuildCraftAPI|statements (1.1) from MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar
		* BuildCraftAPI|tablet (1.0) from MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar
		* BuildCraftAPI|tiles (1.2) from MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar
		* BuildCraftAPI|tools (1.0) from MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar
		* BuildCraftAPI|transport (5.0) from MineFactoryReloaded-[1.10.2]2.9.0B1-215.jar
		* CoFHAPI (1.8.9R1.2.0B1) from rangedpumps-0.3.jar
		* cofhapi (1.5.0) from ActuallyAdditions-1.10.2-r105.jar
		* cofhapi|block (1.7.0) from CoFHCore-1.10.2-4.1.4.7-universal (1).jar
		* CoFHAPI|core (1.8.9R1.2.0B1) from valkyrielib-1.10.2-0.10.6.jar
		* cofhapi|core (1.6.0) from zerocore-1.10.2-0.1.0.5.jar
		* CoFHAPI|energy (1.8.9R1.2.0B1) from SolarFluxReborn_1.10.2-2.16r.jar
		* cofhapi|energy (1.5.0) from ImmersiveEngineering-0.10-58.jar
		* CoFHAPI|inventory (1.8.9R1.2.0B1) from valkyrielib-1.10.2-0.10.6.jar
		* CoFHAPI|item (1.8.9R1.2.0B1) from valkyrielib-1.10.2-0.10.6.jar
		* cofhapi|item (1.6.0) from zerocore-1.10.2-0.1.0.5.jar
		* cofhapi|tileentity (1.6.0) from zerocore-1.10.2-0.1.0.5.jar
		* cofhapi|util (1.7.0) from CoFHCore-1.10.2-4.1.4.7-universal (1).jar
		* cofhlib (1.7.1) from CoFHCore-1.10.2-4.1.4.7-universal (1).jar
		* cofhlib|audio (1.7.1) from CoFHCore-1.10.2-4.1.4.7-universal (1).jar
		* cofhlib|gui (1.7.1) from CoFHCore-1.10.2-4.1.4.7-universal (1).jar
		* cofhlib|gui|container (1.7.1) from CoFHCore-1.10.2-4.1.4.7-universal (1).jar
		* cofhlib|gui|element (1.7.1) from CoFHCore-1.10.2-4.1.4.7-universal (1).jar
		* cofhlib|gui|element|listbox (1.7.1) from CoFHCore-1.10.2-4.1.4.7-universal (1).jar
		* cofhlib|gui|slot (1.7.1) from CoFHCore-1.10.2-4.1.4.7-universal (1).jar
		* cofhlib|inventory (1.7.1) from CoFHCore-1.10.2-4.1.4.7-universal (1).jar
		* cofhlib|util (1.7.1) from CoFHCore-1.10.2-4.1.4.7-universal (1).jar
		* cofhlib|util|helpers (1.7.1) from CoFHCore-1.10.2-4.1.4.7-universal (1).jar
		* cofhlib|world (1.7.1) from CoFHCore-1.10.2-4.1.4.7-universal (1).jar
		* cofhlib|world|feature (1.7.1) from CoFHCore-1.10.2-4.1.4.7-universal (1).jar
		* commoncapabilities|api (0.0.1) from CommonCapabilities-1.9.4-1.3.2.jar
		* compatlayer (0.2.9) from compatlayer-1.10-0.2.9.jar
		* ComputerCraft|API (1.80pr0) from zerocore-1.10.2-0.1.0.5.jar
		* ComputerCraft|API|FileSystem (1.80pr0) from zerocore-1.10.2-0.1.0.5.jar
		* ComputerCraft|API|Lua (1.80pr0) from zerocore-1.10.2-0.1.0.5.jar
		* ComputerCraft|API|Media (1.80pr0) from zerocore-1.10.2-0.1.0.5.jar
		* ComputerCraft|API|Peripheral (1.80pr0) from zerocore-1.10.2-0.1.0.5.jar
		* ComputerCraft|API|Permissions (1.80pr0) from zerocore-1.10.2-0.1.0.5.jar
		* ComputerCraft|API|Redstone (1.80pr0) from zerocore-1.10.2-0.1.0.5.jar
		* ComputerCraft|API|Turtle (1.80pr0) from zerocore-1.10.2-0.1.0.5.jar
		* DR-API (1.0.4-Beta) from deepresonance-1.1x-1.4.8.jar
		* DraconicEvolution|API (1.3) from Draconic-Evolution-1.10.2-2.0.10.199-universal.jar
		* ElecCoreAPI (1.0) from ElecCore-1.10.2-1.7.418.jar
		* ElecCore|Abilities (#API_VER#) from ElecCore-1.10.2-1.7.418.jar
		* EnderIOAPI (0.0.2) from EnderIO-1.10.2-3.1.192.jar
		* EnderIOAPI|Redstone (0.0.2) from EnderIO-1.10.2-3.1.192.jar
		* EnderIOAPI|Teleport (0.0.2) from EnderIO-1.10.2-3.1.192.jar
		* EnderIOAPI|Tools (0.0.2) from EnderIO-1.10.2-3.1.192.jar
		* environmentaltech-api (1.10.2-0.10.6b) from environmentaltech-1.10.2-0.10.6b.jar
		* fluxapi (1.0) from FluxNetworks-1.10.2-1.2.3.jar
		* ForestryAPI|apiculture (5.0.0) from forestry_1.10.2-5.2.17.368.jar
		* ForestryAPI|arboriculture (4.2.1) from forestry_1.10.2-5.2.17.368.jar
		* ForestryAPI|circuits (3.1.0) from forestry_1.10.2-5.2.17.368.jar
		* ForestryAPI|climate (2.1.0) from forestry_1.10.2-5.2.17.368.jar
		* ForestryAPI|core (5.1.0) from forestry_1.10.2-5.2.17.368.jar
		* ForestryAPI|farming (2.1.0) from forestry_1.10.2-5.2.17.368.jar
		* ForestryAPI|food (1.1.0) from forestry_1.10.2-5.2.17.368.jar
		* ForestryAPI|fuels (3.0.0) from forestry_1.10.2-5.2.17.368.jar
		* ForestryAPI|genetics (4.7.1) from forestry_1.10.2-5.2.17.368.jar
		* ForestryAPI|greenhouse (5.2.0) from forestry_1.10.2-5.2.17.368.jar
		* ForestryAPI|hives (4.1.0) from forestry_1.10.2-5.2.17.368.jar
		* ForestryAPI|lepidopterology (1.3.0) from forestry_1.10.2-5.2.17.368.jar
		* ForestryAPI|mail (3.1.0) from forestry_1.10.2-5.2.17.368.jar
		* ForestryAPI|multiblock (3.0.0) from forestry_1.10.2-5.2.17.368.jar
		* ForestryAPI|recipes (5.4.0) from forestry_1.10.2-5.2.17.368.jar
		* ForestryAPI|storage (5.0.0) from forestry_1.10.2-5.2.17.368.jar
		* ForestryAPI|world (2.1.0) from forestry_1.10.2-5.2.17.368.jar
		* Guide-API|API (1.10.2-2.0.3-46) from Guide-API-1.10.2-2.0.3-46.jar
		* ImmersiveEngineering|API (1.0) from ImmersiveEngineering-0.10-58.jar
		* ImmersiveEngineering|ImmersiveFluxAPI (1.0) from ImmersiveEngineering-0.10-58.jar
		* IronBackpacks|API (0.5) from IronBackpacks-1.10.2-2.2.25.jar
		* jeresources|API (0.5.9.3) from JustEnoughResources-1.10.2-0.5.9.3.jar
		* journeymap|client-api (1.3) from journeymap-1.10.2-5.4.6.jar
		* journeymap|client-api-display (1.3) from journeymap-1.10.2-5.4.6.jar
		* journeymap|client-api-event (1.3) from journeymap-1.10.2-5.4.6.jar
		* journeymap|client-api-model (1.3) from journeymap-1.10.2-5.4.6.jar
		* journeymap|client-api-util (1.3) from journeymap-1.10.2-5.4.6.jar
		* JustEnoughItemsAPI (4.10.1) from jei_1.10.2-3.14.7.419.jar
		* lightningcraftAPI (2.7.0) from lightningcraft-2.7.2-[1.10.2].jar
		* mcjtylib_ng (2.3.11) from mcjtylib-1.1x-2.3.11.jar
		* MekanismAPI|core (9.0.0) from Mekanism-1.10.2-9.2.2.301.jar
		* MekanismAPI|energy (9.0.0) from Mekanism-1.10.2-9.2.2.301.jar
		* MekanismAPI|gas (9.0.0) from Mekanism-1.10.2-9.2.2.301.jar
		* MekanismAPI|infuse (9.0.0) from Mekanism-1.10.2-9.2.2.301.jar
		* MekanismAPI|laser (9.0.0) from Mekanism-1.10.2-9.2.2.301.jar
		* MekanismAPI|reactor (9.0.0) from Mekanism-1.10.2-9.2.2.301.jar
		* MekanismAPI|recipe (9.0.0) from Mekanism-1.10.2-9.2.2.301.jar
		* MekanismAPI|transmitter (9.0.0) from Mekanism-1.10.2-9.2.2.301.jar
		* MekanismAPI|util (9.0.0) from Mekanism-1.10.2-9.2.2.301.jar
		* MouseTweaks|API (1.0) from MouseTweaks-2.8-mc1.10.2.jar
		* OpenComputersAPI|Component (6.0.0-alpha) from OpenComputers-MC1.10.2-1.6.2.7.jar
		* OpenComputersAPI|Core (6.0.0-alpha) from OpenComputers-MC1.10.2-1.6.2.7.jar
		* OpenComputersAPI|Driver (6.0.0-alpha) from OpenComputers-MC1.10.2-1.6.2.7.jar
		* OpenComputersAPI|Driver|Item (6.0.0-alpha) from OpenComputers-MC1.10.2-1.6.2.7.jar
		* OpenComputersAPI|Event (6.0.0-alpha) from OpenComputers-MC1.10.2-1.6.2.7.jar
		* OpenComputersAPI|FileSystem (6.0.0-alpha) from OpenComputers-MC1.10.2-1.6.2.7.jar
		* OpenComputersAPI|Internal (6.0.0-alpha) from OpenComputers-MC1.10.2-1.6.2.7.jar
		* OpenComputersAPI|Machine (6.0.0-alpha) from OpenComputers-MC1.10.2-1.6.2.7.jar
		* OpenComputersAPI|Manual (6.0.0-alpha) from OpenComputers-MC1.10.2-1.6.2.7.jar
		* OpenComputersAPI|Network (6.0.0-alpha) from OpenComputers-MC1.10.2-1.6.2.7.jar
		* OpenComputersAPI|Prefab (6.0.0-alpha) from OpenComputers-MC1.10.2-1.6.2.7.jar
		* pressureAPI (1.3.1.22) from pressure-1.3.1.22-mc1.10.2.jar
		* ProjectEAPI (1.10.2-1.0.0) from ProjectE-1.10.2-PE1.2.0.jar
		* railcraft:API|core (3.1.0) from Railcraft_1.10.2-10.1.1.jar
		* RailcraftAPI|bore (2.0.0) from Railcraft_1.10.2-10.1.1.jar
		* RailcraftAPI|carts (2.0.0) from Railcraft_1.10.2-10.1.1.jar
		* RailcraftAPI|charge (3.0.0) from Railcraft_1.10.2-10.1.1.jar
		* RailcraftAPI|crafting (2.0.0) from Railcraft_1.10.2-10.1.1.jar
		* RailcraftAPI|events (2.0.0) from Railcraft_1.10.2-10.1.1.jar
		* RailcraftAPI|fuel (2.0.0) from Railcraft_1.10.2-10.1.1.jar
		* RailcraftAPI|helpers (2.0.0) from Railcraft_1.10.2-10.1.1.jar
		* RailcraftAPI|items (2.1.0) from Railcraft_1.10.2-10.1.1.jar
		* RailcraftAPI|locomotive (2.0.0) from Railcraft_1.10.2-10.1.1.jar
		* RailcraftAPI|signals (4.0.0) from Railcraft_1.10.2-10.1.1.jar
		* RailcraftAPI|tracks (4.0.0) from Railcraft_1.10.2-10.1.1.jar
		* reborncoreAPI (2.13.5.136) from RebornCore-1.10.2-2.13.5.136-universal.jar
		* reborncoreAPI|Fuel (2.13.5.136) from RebornCore-1.10.2-2.13.5.136-universal.jar
		* reborncoreAPI|Power (2.13.5.136) from RebornCore-1.10.2-2.13.5.136-universal.jar
		* reborncoreAPI|Recipe (2.13.5.136) from RebornCore-1.10.2-2.13.5.136-universal.jar
		* reborncoreAPI|Tile (2.13.5.136) from RebornCore-1.10.2-2.13.5.136-universal.jar
		* sonarapi (1.0.1) from SonarCore-1.10.2-3.2.7.jar
		* SoulShardsTOW|API (0.1.5) from SoulShards-TOW-1.10.2-2.6.7-48.jar
		* StorageDrawersAPI (1.10.2-1.3.0) from StorageDrawers-1.10.2-3.7.1.jar
		* StorageDrawersAPI|config (1.10.2-1.3.0) from StorageDrawers-1.10.2-3.7.1.jar
		* StorageDrawersAPI|event (1.10.2-1.3.0) from StorageDrawers-1.10.2-3.7.1.jar
		* StorageDrawersAPI|inventory (1.10.2-1.3.0) from StorageDrawers-1.10.2-3.7.1.jar
		* StorageDrawersAPI|pack (1.10.2-1.3.0) from StorageDrawers-1.10.2-3.7.1.jar
		* StorageDrawersAPI|registry (1.10.2-1.3.0) from StorageDrawers-1.10.2-3.7.1.jar
		* StorageDrawersAPI|render (1.7.10-1.2.0) from refinedstorage-1.2.26.jar
		* StorageDrawersAPI|storage (1.10.2-1.3.0) from StorageDrawers-1.10.2-3.7.1.jar
		* StorageDrawersAPI|storage-attribute (1.7.10-1.2.0) from refinedstorage-1.2.26.jar
		* theoneprobe_api (1.4.4) from theoneprobe-1.1x-1.4.6.jar
		* valkyrielib.api (1.10.2-0.10.6) from valkyrielib-1.10.2-0.10.6.jar
		* VeinMinerApi (0.3) from VeinMiner-1.9-0.35.3.595+a46c1b0.jar
		* WailaAPI (1.3) from Waila-1.7.0-B3_1.9.4.jar
		* zerocore|API|multiblock (1.10.2-0.0.2) from zerocore-1.10.2-0.1.0.5.jar
		* zerocore|API|multiblock|rectangular (1.10.2-0.0.2) from zerocore-1.10.2-0.1.0.5.jar
		* zerocore|API|multiblock|validation (1.10.2-0.0.2) from zerocore-1.10.2-0.1.0.5.jar
	CodeChickenLib Invalid Fingerprint Reports: 
	CodeChickenCore Invalid Fingerprint Reports: 
	EnderStorage Invalid Fingerprint Reports: 
	EnderIO: Found the following problem(s) with your installation (That does NOT mean that Ender IO caused the crash or was involved in it in any way. We add this information to help finding common problems, not as an invitation to post any crash you encounter to Ender IO's issue tracker. Always check the stack trace above to see which mod is most likely failing.):
                  * Optifine is installed. This is NOT supported.
                  * An unsupportted RF API is installed (1.7.10R1.3.1 from (guessing) jar:file:/C:/Users/steven/Desktop/MultiMC/instances/1.10.2/minecraft/mods/BrandonsCore-1.10.2-2.1.7.102-universal.jar!/cofh/api/CoFHAPIProps.class).
                    Ender IO needs at least 1.4.0 and will NOT work with older versions.
                 This may (look up the meaning of 'may' in the dictionary if you're not sure what it means) have caused the error. Try reproducing the crash WITHOUT this/these mod(s) before reporting it.
	Detailed RF API diagnostics:
                  * RF API class 'EnergyStorage' is loaded from: jar:file:/C:/Users/steven/Desktop/MultiMC/instances/1.10.2/minecraft/mods/BrandonsCore-1.10.2-2.1.7.102-universal.jar!/cofh/api/energy/EnergyStorage.class
                  * RF API class 'IEnergyConnection' is loaded from: jar:file:/C:/Users/steven/Desktop/MultiMC/instances/1.10.2/minecraft/mods/BrandonsCore-1.10.2-2.1.7.102-universal.jar!/cofh/api/energy/IEnergyConnection.class
                  * RF API class 'IEnergyContainerItem' is loaded from: jar:file:/C:/Users/steven/Desktop/MultiMC/instances/1.10.2/minecraft/mods/BrandonsCore-1.10.2-2.1.7.102-universal.jar!/cofh/api/energy/IEnergyContainerItem.class
                  * RF API class 'IEnergyHandler' is loaded from: jar:file:/C:/Users/steven/Desktop/MultiMC/instances/1.10.2/minecraft/mods/BrandonsCore-1.10.2-2.1.7.102-universal.jar!/cofh/api/energy/IEnergyHandler.class
                  * RF API class 'IEnergyProvider' is loaded from: jar:file:/C:/Users/steven/Desktop/MultiMC/instances/1.10.2/minecraft/mods/BrandonsCore-1.10.2-2.1.7.102-universal.jar!/cofh/api/energy/IEnergyProvider.class
                  * RF API class 'IEnergyReceiver' is loaded from: jar:file:/C:/Users/steven/Desktop/MultiMC/instances/1.10.2/minecraft/mods/BrandonsCore-1.10.2-2.1.7.102-universal.jar!/cofh/api/energy/IEnergyReceiver.class
                  * RF API class 'IEnergyStorage' is loaded from: jar:file:/C:/Users/steven/Desktop/MultiMC/instances/1.10.2/minecraft/mods/BrandonsCore-1.10.2-2.1.7.102-universal.jar!/cofh/api/energy/IEnergyStorage.class
                  * RF API class 'ItemEnergyContainer' is loaded from: jar:file:/C:/Users/steven/Desktop/MultiMC/instances/1.10.2/minecraft/mods/BrandonsCore-1.10.2-2.1.7.102-universal.jar!/cofh/api/energy/ItemEnergyContainer.class
                  * RF API class 'TileEnergyHandler' is loaded from: jar:file:/C:/Users/steven/Desktop/MultiMC/instances/1.10.2/minecraft/mods/BrandonsCore-1.10.2-2.1.7.102-universal.jar!/cofh/api/energy/TileEnergyHandler.class
	Detailed Tesla API diagnostics:
                  * Tesla API class 'Tesla' could not be loaded (reason: java.lang.ClassNotFoundException: net.darkhax.tesla.Tesla)
                  * Tesla API class 'TeslaCapabilities' could not be loaded (reason: java.lang.ClassNotFoundException: net.darkhax.tesla.capability.TeslaCapabilities)
                  * Tesla API class 'ITeslaConsumer' could not be loaded (reason: java.lang.ClassNotFoundException: net.darkhax.tesla.api.ITeslaConsumer)
                  * Tesla API class 'ITeslaHolder' could not be loaded (reason: java.lang.ClassNotFoundException: net.darkhax.tesla.api.ITeslaHolder)
                  * Tesla API class 'ITeslaProducer' could not be loaded (reason: java.lang.ClassNotFoundException: net.darkhax.tesla.api.ITeslaProducer)
                  * Tesla API class 'BaseTeslaContainer' could not be loaded (reason: java.lang.ClassNotFoundException: net.darkhax.tesla.api.implementation.BaseTeslaContainer)
                  * Tesla API class 'BaseTeslaContainerProvider' could not be loaded (reason: java.lang.ClassNotFoundException: net.darkhax.tesla.api.implementation.BaseTeslaContainerProvider)
                  * Tesla API class 'InfiniteTeslaConsumer' could not be loaded (reason: java.lang.ClassNotFoundException: net.darkhax.tesla.api.implementation.InfiniteTeslaConsumer)
                  * Tesla API class 'InfiniteTeslaConsumerProvider' could not be loaded (reason: java.lang.ClassNotFoundException: net.darkhax.tesla.api.implementation.InfiniteTeslaConsumerProvider)
                  * Tesla API class 'InfiniteTeslaProducer' could not be loaded (reason: java.lang.ClassNotFoundException: net.darkhax.tesla.api.implementation.InfiniteTeslaProducer)
                  * Tesla API class 'InfiniteTeslaProducerProvider' could not be loaded (reason: java.lang.ClassNotFoundException: net.darkhax.tesla.api.implementation.InfiniteTeslaProducerProvider)

	!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
