# With knowledge of C++, you can call another built in function we have called EquipCosmetics
- Equip cosmetics has 4 parameters that are strings:
```EquipCosmetics(SkinID, BackBlingID, PickaxeID, GliderID, ContrailID, ShoeID);```
- If you want to equip one cosmetic at a time, or less than 6, for the empty cosmetic you want to place "nullptr" to make that slot null:
```EquipCosmetics("CID_028_Athena_Commando_F", nullptr, nullptr, nullptr, nullptr, nullptr);```
