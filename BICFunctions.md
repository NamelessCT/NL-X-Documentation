# List of BIC functions (built in). Be sure to read ScriptCreationAndInterpretation.md to understand the syntax.

# Integer Based Functions

demospeed (int) --- Changes your client speed. Some guns work server-sided. Ex: demospeed 10, demospeed 20, etc. 
fov (int) --- Changes your Field of View. Ex: fov 90, fov 12, etc.

# Spawning (These are client sided, and so is collision, unless you are in a vehicle)

*Debugging*

toggletargetinfo --- Toggles information on where your crosshair is positioned

*Objects*

- summon DefaultPawn --- Summons the unreal engine default pawn
- summon BP_VictoryDrone_C --- Drone that carries away an eliminated player/a player that one
- summon BGA_RiftPortal_Item_Athena_C --- Spawns a rift in the sky

*Builds*

- summon PBWA_M1_Archway_C --- Build
- summon PBWA_M1_ArchwayLarge_C --- Build
- summon PBWA_M1_ArchwayLargeSupport_C --- Build
- summon PBWA_M1_BalconyD_C --- Build
- summon PBWA_M1_BalconyI_C --- Build
- summon PBWA_M1_BalconyO_C --- Build
- summon PBWA_M1_BalconyS_C --- Build
- summon PBWA_M1_Brace_C --- Build
- summon PBWA_M1_DoorC_C --- Build
- summon PBWA_M1_DoorS_C --- Build
- summon PBWA_M1_DoorSide_C --- Build
- summon PBWA_M1_Floor_C --- Build
- summon PBWA_M1_HalfWall_C --- Build
- summon PBWA_M1_HalfWallDoor_C --- Build
- summon PBWA_M1_HalfWallDoorS_C --- Build
- summon PBWA_M1_HalfWallHalf_C --- Build
- summon PBWA_M1_Pillar_C --- Build
- summon PBWA_M1_QuarterWallHalf_C --- Build
- summon PBWA_M1_QuarterWallS_C --- Build
- summon PBWA_M1_RoofC_C --- Build
- summon PBWA_M1_RoofD_C --- Build
- summon PBWA_M1_RoofI_C --- Build
- susmmon PBWA_M1_RoofO_C --- Build
- summon PBWA_M1_RoofS_C --- Build
- summon PBWA_M1_RoofWall_C --- Build
- summon PBWA_M1_Solid_C --- Build
- summon PBWA_M1_StairF_C --- Build
- summon PBWA_M1_StairR_C --- Build
- summon PBWA_M1_StairT_C --- Build
- summon PBWA_M1_StairW_C --- Build
- summon PBWA_M1_WindowC_C --- Build
- summon PBWA_M1_Windows_C --- Build
- summon PBWA_M1_WindowSide_C --- Build
- summon PBWA_S1_Archway_C --- Build
- summon PBWA_S1_ArchwayLarge_C --- Build
- summon PBWA_S1_ArchwayLargeSupport_C --- Build
- summon PBWA_S1_BalconyD_C --- Build
- summon PBWA_S1_BalconyI_C --- Build
- summon PBWA_S1_BalconyO_C --- Build
- summon PBWA_S1_BalconyS_C --- Build
- summon PBWA_S1_Brace_C --- Build
- summon PBWA_S1_DoorC_C --- Build
- summon PBWA_S1_DoorS_C --- Build
- summon PBWA_S1_DoorSide_C --- Build
- summon PBWA_S1_Floor_C --- Build
- summon PBWA_S1_HalfWallDoor_C --- Build
- summon PBWA_S1_HalfWallDoorSide_C --- Build
- summon PBWA_S1_HalfWallHalf_C --- Build
- summon PBWA_S1_HalfWallS_C --- Build
- summon PBWA_S1_Pillar_C --- Build
- summon PBWA_S1_QuarterWallHalf_C --- Build
- summon PBWA_S1_QuarterWallS_C --- Build
- summon PBWA_S1_RoofC_C --- Build
- summon PBWA_S1_RoofD_C --- Build
- summon PBWA_S1_RoofI_C --- Build
- summon PBWA_S1_RoofO_C --- Build
- summon PBWA_S1_RoofS_C --- Build
- summon PBWA_S1_RoofWall_C --- Build
- summon PBWA_S1_Solid_C --- Build
- summon PBWA_S1_StairF_C --- Build
- summon PBWA_S1_StairR_C --- Build
- summon PBWA_S1_StairT_C --- Build
- summon PBWA_S1_StairW_C --- Build
- summon PBWA_S1_Windows_C --- Build
- summon PBWA_S1_WindowsC_C --- Build
- summon PBWA_S1_WindowsSide_C --- Build
- summon PBWA_W1_Archway_C --- Build
- summon PBWA_W1_ArchwayLarge_C --- Build
- summon PBWA_W1_ArchwayLargeSupport_C --- Build
- summon PBWA_W1_BalconyD_C --- Build
- summon PBWA_W1_BalconyI_C --- Build
- summon PBWA_W1_BalconyO_C --- Build
- summon PBWA_W1_BalconyS_C --- Build
- summon PBWA_W1_Brace_C --- Build
- summon PBWA_W1_DoorC_C --- Build
- summon PBWA_W1_DoorS_C --- Build
- summon PBWA_W1_DoorSide_C --- Build
- summon PBWA_W1_Floor_C --- Build
- summon PBWA_W1_HalfWallDoor_C --- Build
- summon PBWA_W1_HalfWallDoorS_C --- Build
- summon PBWA_W1_HalfWallHalf_C --- Build
- summon PBWA_W1_HalfWallS_C --- Build
- summon PBWA_W1_Pillar_C --- Build
- summon PBWA_W1_QuarterWallHalf_C --- Build
- summon PBWA_W1_QuarterWallS_C --- Build
- summon PBWA_W1_RoofC_C --- Build
- summon PBWA_W1_RoofD_C --- Build
- summon PBWA_W1_RoofI_C --- Build
- summon PBWA_W1_RoofO_C --- Build
- summon PBWA_W1_RoofS_C --- Build
- summon PBWA_W1_RoofWall_C --- Build
- summon PBWA_W1_Solid_C --- Build
- summon PBWA_W1_StairF_C --- Build
- summon PBWA_W1_StairR_C --- Build
- summon PBWA_W1_StairSpiral_C --- Build
- summon PBWA_W1_StairT_C --- Build
- summon PBWA_W1_StairW_C --- Build
- summon PBWA_W1_WindowC_C --- Build
- summon PBWA_W1_Windows_C --- Build
- summon PBWA_W1_WindowSide_C --- Build
